[← Voltar](index.md)

# Funcionalidades

## Vendas (`/vendas`)
Lançamento de vendas por loja, data e turno (Manhã / Noite).

Três fontes de receita, dependendo da loja:
- **Salão** (mesa) — Flamengo e Barra. Sincroniza automático com o Colibri (sistema de caixa dos restaurantes). Admin clica em "Sincronizar" e o valor + quantidade de mesas do dia entram automático, já separados por turno (antes das 18h = Manhã, 18h+ = Noite).
- **Delivery** (iFood, 99Food, Brendi, Delivery Direto) — lançamento manual em Flamengo/Barra (pedidos via tablet do parceiro, fora do Colibri). Em Nema, sincroniza automático com o Saipos.
- **Balcão** — só em Nema (padaria). Sincroniza automático com o Saipos.

Card "Resumo" mostra o total do turno em tempo real conforme você digita.

## Manutenção (`/manutencao`)
Cadastro e acompanhamento de tarefas de manutenção por loja, com:
- Categoria, setor, prioridade, status
- Fornecedor/responsável vinculado (puxado da lista de Fornecedores)
- Histórico de tarefas concluídas

## Fornecedores (`/fornecedores`)
Cadastro de fornecedores/prestadores de serviço por loja (ou compartilhado entre lojas). Usado também no módulo de Manutenção para vincular quem é responsável por cada tarefa.

## Compras (`/compras`)
Controle de compras/insumos por loja.

## Reservas (`/reservas`)
Reservas de mesa (restaurantes).

## Operação (`/operacao`)
Painel do dia: eventos do calendário + reservas do dia, por loja.

## Concessionária (`/concessionaria`)
Controle de consumo de utilidades (energia, água, gás) por loja — leituras e tarifas.

## RH (`/rh`)
Gestão de equipe.

## Calendário (`/calendario`)
Eventos e compromissos por loja.

## Admin (`/admin`)
Painel exclusivo do administrador — gestão de usuários, lojas e configurações gerais.

## Início (`/`)
Dashboard inicial — visão consolidada do dia (todas as lojas ou loja selecionada).
