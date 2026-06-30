[← Voltar](index.md)

# Evolução

Histórico de mudanças relevantes do app. Mais recente primeiro.

## 2026-06

- **Split de turno por horário/dado real.** Antes, o turno gravado era "o que estava ativo na aba" quando clicava Sincronizar — causava dado indo todo pra Manhã. Agora: Colibri usa horário da venda (corte 18h), Saipos usa o campo de turno do próprio sistema. Turno "Tarde" removido (não existia de fato pra nenhuma loja).
- **Quantidade de Salão.** Sincronizar Colibri não gravava a quantidade de mesas (`clientes`), só o valor. Corrigido — quantidade agora vem de `modo_breakdown.MESA.quantidade`.
- **Cards por loja.** Vendas agora mostra só o que existe em cada loja: Nema não tem Salão, Flamengo/Barra não têm Balcão nem sync Saipos.
- **Quantidade no Colibri.** Endpoint `modo-venda` do Colibri usado pra trazer quantidade de vendas por modo (Mesa/Balcão/Entrega/Ficha), não só o valor total.

## Decisões confirmadas com o dono

- Colibri (Flamengo/Barra) é usado só pra Salão — delivery desses restaurantes não passa pelo Colibri, é direto com cada plataforma (iFood etc).
- Nema (padaria) não tem Salão — só Delivery e Balcão, via Saipos.
