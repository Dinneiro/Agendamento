# Ateliê — Sistema de Agendamento

Protótipo responsivo para organizar serviços, horários e reservas de clientes.

## Recursos

- Tela de acesso demonstrativa.
- Cadastro e remoção de serviços, com duração e preço.
- Agenda semanal com atendimentos marcados.
- Cadastro manual de horários pelo painel.
- Página pública de reserva com seleção de serviço, data e horário.
- Bloqueio dos horários já ocupados na data escolhida.
- Persistência local usando `localStorage`.

## Como executar

1. Baixe `agendamento.html`.
2. Abra o arquivo em um navegador atualizado.
3. Para acessar a demonstração, use qualquer e-mail e uma senha com pelo menos quatro caracteres.
4. No menu, abra **Serviços** para cadastrar opções ou **Link de agendamento** para ver a página de reservas.

Não há instalação de dependências nem etapa de build.

## Tecnologias

- HTML
- CSS
- JavaScript
- `localStorage` e `sessionStorage` do navegador

## Dados de demonstração

O calendário começa com serviços e atendimentos fictícios. A tela de acesso apenas simula uma sessão; não valida credenciais nem cria uma conta real.

## Limitações

- Os dados existem somente no navegador e dispositivo usados.
- A página de reserva não envia e-mail ou notificações.
- A autenticação não oferece segurança real.
- O calendário demonstra uma semana e as setas de navegação não alteram o período.

## Próximas melhorias

- Implementar autenticação e banco de dados.
- Gerar disponibilidade com regras de expediente, intervalos e folgas.
- Adicionar confirmação, cancelamento e reagendamento.
- Enviar notificações por e-mail ou WhatsApp.
- Oferecer visualizações de calendário mensal e semanal navegáveis.
