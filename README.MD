<div style="display: flex; align-items: center; justify-content: center;margin-top: 30px;">
    <img src="/.github/assets/logo.svg" alt="Ecoleta" style="height: 90px;">
</div>
<div style="display: flex; align-items: center; justify-content: center; margin-top: 40px;flex-direction: row;">
    <img src="https://img.shields.io/github/last-commit/MichelCassol/ecoleta" alt="last-commit">&nbsp;&nbsp;&nbsp;
    <img src="https://img.shields.io/github/repo-size/MichelCassol/ecoleta" alt="repo-size">&nbsp;&nbsp;&nbsp;
    <img src="https://img.shields.io/badge/license-MIT-brightgreen" alt="License">
</div>

## :eyeglasses: Preview
### :computer: Web

![Web](.github/assets/web.gif)

### :iphone: Mobile

![Mobile](.github/assets/mobile.gif)


## :rocket: Tecnologias
Tecnologias utilizadas no desenvolvimento desse projeto:
* Node.js
* Typescript
* ReactJS
* Raact Native
* Consumo da Api de endereços do IBGE

## Getting Started
~~~
# Clone o repositório para a sua máquina:
$ git clone https://github.com/MichelCassol/ecoleta.git

# Agora configure o IP da sua máquina nos arquivos:
$ /nlw/server/src/controllers/ItemsController.ts
$ /nlw/server/src/controllers/ItemsController.ts

# Após isso abra cada pasta em uma nova sessão de terminal e execute:
$ npm install

# Na pasta server execute:
$ npm run knex:migrate
$ npm run knex:seed

# Por fim execute os comandos de start:
Server: $ npm run dev
Web:    $ npm start
Mobile: $ npm start
~~~

## Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.