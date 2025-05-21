# Fluxo de Aprovação de Documentos com Power Automate e SharePoint

Este projeto foi desenvolvido como parte do módulo **"Criar fluxos de aprovação com o Power Automate"** da Microsoft Learn.

## 💡 Descrição do Fluxo

Sempre que um novo documento for adicionado à biblioteca do SharePoint, um fluxo é acionado para solicitar aprovação de um usuário designado:

- **Aprovado**: o documento permanece na biblioteca.
- **Rejeitado**: o documento é movido automaticamente para a pasta `Rejected Documents`.

## 🔧 Tecnologias Utilizadas
- Microsoft Power Automate
- SharePoint Online
- Copilot do Power Automate

## 📌 Etapas do fluxo
1. Gatilho: Quando um novo arquivo é criado no SharePoint
2. Ação: Iniciar e aguardar uma aprovação (modelo "Primeiro a responder")
3. Condição:
   - Se aprovado: não faz nada
   - Se rejeitado: move o documento para a pasta de documentos rejeitados
4. Testado com sucesso no ambiente real (sem simulações guiadas)

## 🏁 Resultado
Fluxo funcional, testado com casos reais. Esse tipo de fluxo pode ser adaptado para qualquer cenário que envolva revisão e controle de documentos via SharePoint.

## 📂 Estrutura
- `printscreen_fluxo.png`: captura do fluxo no Power Automate
- `README.md`: descrição do projeto

