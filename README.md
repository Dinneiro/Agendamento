# Clara — Controle Financeiro

Dashboard financeiro responsivo para acompanhar entradas, despesas, saldo e lançamentos recentes.

## Recursos

- Resumo de entradas, despesas e saldo disponível.
- Cadastro de lançamentos com descrição, categoria, tipo, valor e data.
- Histórico ordenado por data.
- Layout adaptado para celular e desktop.
- Persistência local dos lançamentos usando `localStorage`.

## Como executar

1. Baixe `controle-financeiro.html`.
2. Abra o arquivo em um navegador atualizado.
3. Se quiser publicar, adicione o arquivo ao seu repositório e habilite hospedagem estática, como GitHub Pages.

Não há instalação de dependências nem etapa de build.

## Tecnologias

- HTML
- CSS
- JavaScript
- `localStorage` do navegador

## Dados de demonstração

O projeto começa com alguns lançamentos fictícios para preencher o dashboard. Ao adicionar novos registros, os totais e a lista são atualizados. Os dados ficam armazenados somente no navegador e dispositivo usados.

## Limitações

- Não há conta de usuário, API ou sincronização entre dispositivos.
- Os dados iniciais e limites de orçamento são demonstrativos.
- O seletor de período é visual; os lançamentos não são filtrados por mês.

## Próximas melhorias

- Filtrar relatórios por mês e categoria.
- Permitir editar e excluir lançamentos.
- Tornar os limites de orçamento editáveis.
- Adicionar exportação CSV e integração com uma API.
