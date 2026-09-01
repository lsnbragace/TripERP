# TripERP H0.6.10 — Recurring Costs Integration Fix

Correções principais:
- custos recorrentes agora aparecem em cada dia do Roteiro Dia a Dia;
- total diário inclui hospedagem + atividades + recorrentes/provisões;
- orçamento Planejado inclui o impacto efetivo dos recorrentes;
- gráficos por categoria/destino recebem os valores recorrentes;
- detalhamento financeiro mostra provisões aplicadas por data;
- exportação HTML inclui os custos recorrentes no roteiro diário;
- viagens antigas ganham automaticamente a estrutura recurringCosts ao abrir.

Regra Provisão: valor adicionado = max(0, provisão do dia - gasto específico da mesma categoria) + itens configurados como Somar sempre.
