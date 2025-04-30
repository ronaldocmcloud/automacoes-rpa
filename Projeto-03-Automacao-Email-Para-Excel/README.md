# Projeto 3 - Registro automático de e-mails com "Pedido" no assunto

## 📌 Introdução

Este projeto foi desenvolvido no **Power Automate** com o objetivo de automatizar o registro de e-mails que contenham a palavra **"Pedido"** no assunto. O fluxo detecta esses e-mails, extrai suas informações principais e registra automaticamente os dados em uma planilha do Excel, além de enviar uma notificação para o celular do usuário.

Essa automação é útil para centralizar pedidos recebidos por e-mail e garantir rastreabilidade e agilidade no acompanhamento, sem depender de ações manuais.

---

## ⚙️ Tecnologias Utilizadas

- Microsoft Power Automate (Cloud)
- Outlook 365 (e-mail de entrada)
- Excel Online (armazenamento dos dados)
- OneDrive for Business (local do arquivo Excel)
- Aplicativo Power Automate no celular (para notificação push)

---

## ✅ Funcionalidades

- Monitorar a caixa de entrada de e-mails automaticamente
- Filtrar apenas os e-mails com "Pedido" no assunto
- Converter o corpo do e-mail de HTML para texto legível
- Registrar os dados em uma tabela do Excel
- Enviar uma notificação para o celular informando a chegada do pedido

---

## 🧭 Etapas do fluxo

1. **Disparo:** Quando um novo e-mail é recebido
2. **Condição:** Verifica se o assunto contém a palavra “Pedido”
3. **Conversão:** Transforma o corpo HTML do e-mail em texto simples
4. **Registro:** Adiciona uma nova linha na tabela do Excel com os dados:
   - Remetente
   - Assunto
   - Data
   - Corpo do e-mail (texto convertido)
5. **Notificação:** Envia um alerta no celular com o resumo do e-mail

---

## 📸 Prints do Projeto

### 🔄 Fluxo completo no Power Automate
![Fluxo Power Automate](./Projeto-03-Automacao-Email-Para-Excel/fluxo.png)

---

### 📬 Exemplo de E-mail com "Pedido"
![Exemplo de E-mail](./Projeto-03-Automacao-Email-Para-Excel/email.png)

---

### 📊 Registro na Planilha Excel (OneDrive)
![Planilha Excel](./Projeto-03-Automacao-Email-Para-Excel/planilha.png)


---

## 📚 Aprendizados e observações

- ✅ Aprendi a utilizar a ação **"Converter HTML em texto"**, essencial para extrair o conteúdo limpo do corpo do e-mail.
- ✅ Entendi a estrutura dos objetos retornados pelo Outlook no Power Automate e como navegar corretamente por eles.
- ⚠️ Erros comuns foram resolvidos, como tentativas de acessar propriedades de tipo incorreto (por exemplo, acessar `emailAddress` diretamente de uma string).
- 🚀 O fluxo está funcional e pronto para escalar com novos filtros ou integrações futuras.

---


