---
layout: default
title: Arquitetura
---

[← Voltar](./)

# Arquitetura

## Camadas do sistema

- Frontend / SSR
- Hospedagem em nuvem
- Banco de dados
- Estilo e interface
- Build e deploy

## Integrações externas (POS)

| Loja | Sistema POS | O que sincroniza |
|---|---|---|
| Flamengo, Barra | Colibri Cloud | Salão (valor + quantidade de mesas) |
| Nema | Saipos | Delivery (por plataforma) + Balcão |

Chamadas via `fetch` puro (sem SDK Node — runtime é Workers, não Node).

### Split por turno

- **Colibri**: cada venda tem campo `hora`. Antes das 18h → Manhã, 18h+ → Noite.
- **Saipos**: cada venda tem `store_shift.desc_store_shift` ("Dia"/"Noite") — usado direto, sem cálculo de horário.

Não existe mais turno "Tarde" — só Manhã e Noite.

## Segurança / autenticação

- `supabase.auth.getUser()` (nunca `getSession()`) — valida no servidor.
- Cookies de sessão sempre repassados via `headers` em toda Response.
- Segredos (tokens Colibri/Saipos) ficam em `context.cloudflare.env`, nunca em `process.env`.

## Estrutura de pastas (resumo)

```
app/
  routes/        rotas (uma por módulo: vendas, manutencao, fornecedores...)
  lib/
    supabase/    cliente Supabase
    colibri.server.ts   integração Colibri
    saipos.server.ts    integração Saipos
migrations/      SQL do Supabase
```
