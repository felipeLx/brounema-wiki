---
layout: default
title: Como Usar
---

[← Voltar](./)

# Como Usar

## Papéis (perfis de acesso)

- **Admin** (dono) — acesso a todas as lojas, todos os módulos, botões de sincronização (Colibri/Saipos), gerenciamento de usuários.
- **Gerente** — acesso só à(s) loja(s) vinculada(s) ao seu perfil. Não vê botão de sincronizar, não gerencia usuários (só altera a própria senha).

## Login

E-mail + senha cadastrados pelo admin. Após login, o sistema redireciona para a tela Início.

---

## Navegação

Barra inferior fixa com 5 abas:

| Aba | O que faz |
|-----|-----------|
| Início | Dashboard/resumo do dia |
| Operação | Painel consolidado de atividades |
| Vendas | Lançar e sincronizar vendas |
| RH | Presença e pontuação de funcionários |
| Mais | Menu para telas extras |

A tela **Mais** dá acesso a: Compras, Reservas, Admin, Concessionária, Manutenção, Calendário e Fornecedores.

---

## Início (Dashboard)

Resumo diário da loja selecionada.

**Controles:**
- Navegação de data (dia anterior / seguinte / calendário)
- Seletor de turno (Todos / Manhã / Noite)

**Cards visíveis:**
- **Venda Total** — valor do dia com comparação % vs dia anterior e vs mesmo dia do mês anterior. Breakdown: Salão, Delivery, Clientes.
- **Agenda do dia** — contagem de eventos e lista dos 3 primeiros.
- **Salão** — faturamento com variação %.
- **Delivery** — faturamento com variação %.
- **Checklist** — progresso (X/Y itens). Expandir para marcar, editar, excluir ou adicionar itens.
- **Equipe** — presentes/faltas do dia.
- **Leituras** — últimas leituras de energia/água/gás com variação %.
- **Lançar vendas** — atalho indicando se já foi preenchido.

**Ações:** marcar/editar/excluir/adicionar itens de checklist, navegar para outras telas via atalhos.

---

## Vendas

Lançamento e sincronização das vendas diárias por turno (Manhã / Noite).

**Passo a passo:**
1. Escolha a loja (se admin com mais de uma).
2. Escolha a data e o turno.
3. Se admin, clique **Sincronizar** no card do PDV (Colibri ou Saipos) para puxar valores automáticos.
4. Preencha manualmente o que não sincroniza.
5. Confira o **Resumo** (calculado em tempo real) e clique **Salvar Vendas**.

**Seções do formulário:**
- **Delivery** — por plataforma: campos Pedidos e Valor. Botão "+ Plataforma" para cadastrar nova.
- **Salão** (lojas com salão) — Quantidade de clientes e Faturamento.
- **Balcão** (loja Nema) — Pedidos e Faturamento.
- **Observações** — campo livre.

> Sincronizar de novo no mesmo dia atualiza os valores (não duplica).

---

## Operação

Painel consolidado das atividades do dia — visualização rápida sem criação.

**Seções:**
- **Compras** — lista de compras pendentes/entregues. Botões "✓ Entregue" e "✕ Cancelar" por item.
- **Reservas** — horário, cliente, pessoas, telefone, observações.
- **Manutenção** — tarefas pendentes/em andamento com setor e prioridade.
- **Agenda** — eventos do calendário (reunião/visita/geral).

---

## RH

Gestão de presença, status e pontuação de funcionários.

**Cards de resumo:** Presentes, Faltas, Atestado, Férias.

**Filtros:** Todos / Presente / Falta / Atestado / Férias / Inativo.

**Para cada funcionário (expandir clicando):**
- **Presença hoje** — botões rápidos: ✓ Presente / ✕ Falta / ⊘ Atestado
- **Status** — Ativo / Férias / Desativar
- **Pontuação** — total de pontos; botão "+/- Pontuar" para adicionar pontos positivos ou negativos com motivo

**Ações:** adicionar funcionário (nome, CPF, cargo, loja), registrar presença, alterar status, pontuar.

---

## Compras

Gerenciar compras de insumos.

**Criar compra:** botão "+ Nova compra" → Produto, Quantidade, Unidade (un/kg/g/L/ml/cx/pct), Valor (R$), Previsão de entrega, Observações.

**Lista de pendentes:** cada item mostra produto, quantidade, valor, prazo. Botões "✓ Entregue" e "✕ Cancelar".

---

## Reservas

Gerenciar reservas de mesa por loja e data.

**Criar reserva:** botão "+ Reserva" → Data, Hora, Nome do cliente, Quantidade de pessoas, Telefone (opcional), Observações.

**Lista do dia:** horário, pessoas, cliente, telefone, observações. Botão "Excluir" por reserva.

---

## Concessionária

Controle de consumo e custo de utilidades.

**Abas:** ⚡ Energia / 💧 Água / 🔥 Gás

**Cards:**
- Última leitura, Variação % vs mês anterior, Média de 3 meses.
- **Projeção mensal** — custo estimado (consumo × tarifa). Botão "⚙ Tarifa" para configurar valor por unidade.

**Ações:**
- Registrar nova leitura (data, valor, observações).
- Ver gráfico de consumo mensal (últimos 12 registros + média móvel).
- Excluir leitura do histórico.

---

## Manutenção

Kanban de tarefas de manutenção por setor.

**Cards de resumo:** Pendentes, Em andamento, Concluídas.

**Criar tarefa:** Título, Descrição, Setor, Prioridade (baixa/média/alta/urgente), Loja, Fornecedor/Responsável, Data agendada, Horário.

**Criar setor:** ícone (emoji) + nome.

**Kanban (aba Ativas):**
- Coluna "⏳ Pendentes" e "🔄 Em andamento"
- Expandir card para ver descrição e botões: ▶ Iniciar / ✓ Concluir / ✕ Cancelar

**Aba Histórico:** últimas 10 tarefas concluídas/canceladas.

**Contatos de manutenção:** lista de fornecedores da categoria "manutenção" com botões de ligar/email.

---

## Calendário

Agenda de eventos gerais.

**Criar evento:** botão "+ Novo Evento" → Título, Descrição, Data, Horário, Categoria (Reunião/Visita/Manutenção/Entrega/Geral), Loja (Todas ou específica).

**Lista do dia:** ícone por categoria, horário, título, descrição, badges de categoria e loja. Botão excluir (✕) por evento.

---

## Fornecedores

Cadastro de contatos e fornecedores por categoria.

**Criar fornecedor:** botão "+ Novo" → Nome, Categoria (Fornecedor/Manutenção/Reserva/Geral), Loja (Todas ou específica), Telefone, Email, Observações.

**Lista:** expandir para ver telefone (link direto para ligar), email (link direto para enviar), observações. Botões "✎ Editar" e "✕ Remover".

> Gerente vê apenas fornecedores da própria loja + os globais.

---

## Admin

Gerenciamento de usuários — **acesso restrito a admin**.

**Disponível para todos:**
- Card "Alterar senha" — nova senha + confirmação.

**Apenas admin (abas Ger. / Adm. / Func.):**
- **Criar gerente/admin:** Nome, Email, CPF, Função, Lojas (múltiplas), Senha temporária.
- **Criar funcionário:** Nome, CPF, Cargo, Loja.
- **Editar** usuário/funcionário existente (nome, CPF, função, lojas).
- Lista mostra avatar, nome, role, lojas vinculadas, CPF.

> Gerentes veem apenas o card de alterar senha nesta tela.
