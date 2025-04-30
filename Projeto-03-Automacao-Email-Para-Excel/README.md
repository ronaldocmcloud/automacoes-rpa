## Projeto 03 – Automação: Registro de e-mails com “Pedido” em Excel via Power Automate

### Descrição
Este projeto utiliza o Power Automate para monitorar a caixa de entrada do Outlook. Quando um e-mail com a palavra “Pedido” no assunto é recebido, os dados do remetente, assunto, data e corpo do e-mail são extraídos, convertidos de HTML para texto, armazenados em uma planilha Excel no OneDrive e uma notificação é enviada para o celular.

### Funcionalidades:
- Detecção automática de e-mails com “Pedido” no assunto
- Conversão de corpo do e-mail de HTML para texto limpo
- Registro em planilha Excel no OneDrive
- Notificação móvel via app Power Automate

### Aprendizados:
- Uso de condições lógicas no Power Automate
- Manipulação de conteúdo HTML
- Integração entre Outlook, Excel e notificações móveis
- Tratamento de erros comuns com expressões como `formatDateTime` e `convertFromHtml`

### Screenshot do fluxo:
![Fluxo Power Automate](./Projeto-03-Automacao-Email-Para-Excel/fluxo.png)
