## requisitos:
- uma aplicação do Discord que contenha um bot com Privileged Gateways Intents permitidos e habilitados 
- Node.js
- algum editor, como VSCode
- (e o basico de java script)

# como usar:
- abra o terminal, e executa os seguintes comandos:
  - esse comando cria o arquivo package.json:
  > npm init -y
  
  - instala os pacotes dotenv e discord.js:
  > npm install discord.js dotenv
  
  - instala os pacotes do nodemon, ferramenta que auxilia na execução de aplicações baseadas em Node.js:
  > npm install -g nodemon

- crie um arquivo chamado ```.env```, que contém o token do bot declarado como ```TOKEN = xxxxxxxxxxxxxxxxxxxxxx```.
- crie um arquivo chamado ```index.js```, com o código base do bot, que contém métodos de login e interação.
- depois dos arquivos criados, basta executar digitando ```nodemon``` no terminal.

Encontre documentação para interação no site oficial do [discord.js](https://discord.js.org/#/)
