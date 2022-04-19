# Otimization App - Raro Academy

Projeto desenvolvido para praticar otimizações de aplicações React, parte da avaliação do curso da Raro Academy - semana 08.

## Otimizações chat

* Utilização de key no map de renderização do component ChatMessageList
* Utilização do Debounce no input de pesquisa das mensagens
* Utilização do hook memo na renderização dos componentes MyChatMessage e ChatMessage

## Otimização color responsive
* Aplicação do debounce na rerenderização da página

### Como rodar e observações

- Baixar o projeto ou fazer o clone da pasta.
- Executar no diretório do projeto os comandos _npm install_ e _npm start_.
- O arquivo src/App.tsx vem com o componente Chat como componente principal. Para trocar para o ColorResponsive, deve-se editar este arquivo comentando o componente Chat e sua importação, e removendo as barras de comentário do componente ColorResponsive e sua importação.
- Obs.: Ainda há espaço de melhorias, entre elas a sintaxe do arquivo src/index.tsx de acordo com a nova versão do React, assim removendo a duplicidade de renderização ao iniciar a aplicação.
