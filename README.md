# TripERP H0.6.6 — Daily Planner & Financial Dashboard

Versão funcional para homologação.

## Principais revisões
- Hospedagens agora são editáveis/revisáveis após o cadastro.
- Valor da hospedagem é tratado como valor total da reserva.
- Número de noites e valor médio por noite são calculados automaticamente.
- Vários hotéis podem ser cadastrados na mesma cidade.
- No Roteiro Dia a Dia é possível escolher o hotel de cada noite.
- Alertas de hospedagem ausente e conflito entre hotéis.
- Experiências marcadas passam a alimentar o Roteiro Dia a Dia e o mapa.
- Agenda diária completa com lugares, restaurantes, tours, bate-voltas, transporte local, compras, tempo livre e outros.
- Atividades têm horário, tipo, local, duração, custo, moeda, reserva e status.
- Atividades podem ser reordenadas dentro do dia.
- Orçamento usa o valor total da reserva de hotel apenas uma vez, evitando duplicidade.
- Painel financeiro com gráficos por categoria, por destino e Planejado × Reservado × Pago.
- KPIs: orçamento, planejado, reservado, pago, saldo, média/dia e custo/viajante.
- Campo renomeado para “Margem de segurança cambial (%)”.
- Mantidos mapa real, roteiro reordenável, Geoapify, multimoeda e viagem ativa.

## Observações
Os gráficos usam Chart.js carregado por CDN. O mapa usa Leaflet e tiles Geoapify.
