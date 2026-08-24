# TripERP H0.5 — Arquitetura Funcional

## Conceito
O TripERP deixa de tratar o cadastro de cidades como uma ordem de viagem. Primeiro entende-se o problema da viagem; depois são avaliados destinos, interesses, tempo, rota e logística.

## Fluxo
1. Configuração — origem, retorno, datas, viajantes e orçamento.
2. Destinos candidatos — lugares desejados, sem ordem.
3. Interesses & descoberta — interesses e pontos de interesse.
4. Distribuição de tempo — sugestão de dias por destino.
5. Roteiro inteligente — alternativas de sequência.
6. Mapa central — visão transversal da viagem.
7. Aprovação — editar, recalcular ou aprovar.
8. Roteiro oficial — proposta aprovada.
9. Logística — voos, transporte e hotéis.
10. Orçamento — meta, estimado, reservado e realizado.
11. TripERP Insight — recomendações e alertas.
12. Manual — apoio ao usuário.

## Estados
- Candidato
- Sugerido
- Aprovado
- Visitado (evolução futura)

## Decisões
- O usuário não precisa informar latitude/longitude manualmente.
- Origem e retorno são parte da configuração.
- Destinos podem ser cadastrados em qualquer ordem.
- A sequência é uma decisão posterior do mecanismo de planejamento.
- O mapa é componente transversal.
- O usuário aprova o roteiro; o assistente recomenda, mas não decide sozinho.

## Evoluções previstas
Geocodificação automática, mapas reais, APIs de voos/hotéis, POIs reais, otimização de rotas, persistência, autenticação, calendário e assistente com dados persistentes do projeto.
