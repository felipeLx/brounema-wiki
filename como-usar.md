---
layout: default
title: Como Usar
---

[← Voltar](./)

# Como Usar

## Papéis (perfis de acesso)

- **Admin** (dono) — acesso a todas as lojas, todos os módulos, botões de sincronização (Colibri/Saipos).
- **Gerente** — acesso só à(s) loja(s) vinculada(s) ao seu perfil. Não vê botão de sincronizar (só admin sincroniza POS).

## Login

`/auth/login` — e-mail + senha cadastrados pelo admin.

## Lançar vendas do dia

1. Abra **Vendas**.
2. Escolha a loja (se for admin com mais de uma loja).
3. Escolha a data (padrão: hoje).
4. Escolha o turno: **Manhã** ou **Noite**.
5. Se a loja sincroniza automático (Salão em Flamengo/Barra, Delivery+Balcão em Nema) e você é admin, clique em **Sincronizar** no card correspondente — os valores entram sozinhos.
6. Preencha manualmente o que não sincroniza (Delivery em Flamengo/Barra, por enquanto).
7. Confira o card **Resumo** e clique em **Salvar Vendas**.

> Sincronizar de novo no mesmo dia atualiza os valores (não duplica).

## Cadastrar uma tarefa de manutenção

1. Abra **Manutenção**.
2. Preencha categoria, setor, descrição, prioridade.
3. Se for um serviço de terceiro, selecione o **Fornecedor/Responsável** (lista vem de Fornecedores — cadastre lá primeiro se não existir).
4. Salvar.

## Cadastrar um fornecedor

1. Abra **Fornecedores**.
2. Nome, categoria, loja (ou deixe sem loja para aparecer em todas).
3. Salvar — já fica disponível no formulário de Manutenção.
