# JSExpertMax Gesture Controller - Semana JS Expert 7.0
O projeto foi desenvolvido durante a Semana JS Expert 7.0, tendo como objetivo ser uma aplicação de controle de páginas HTML através de gestos das mãos, através da utilização da lib Tensorflow, utilizando de machine learning e multi threading direto no navegador, a versão final resultante da semana pode ser acessada aqui: https://keftondavid.github.io/semana-javascript-expert07/classes/class04


## Preview
<img width=100% src="./initial-template/assets/demo-template-lg.gif">

## Pre-reqs
- Este projeto foi criado usando Node.js v19.6
- O ideal é que você use o projeto em ambiente Unix (Linux). Se você estiver no Windows, é recomendado que use o [Windows Subsystem Linux](https://www.omgubuntu.co.uk/how-to-install-wsl2-on-windows-10) pois nas aulas são mostrados comandos Linux que possam não existir no Windows.

## Running
- Execute `npm ci` na pasta que contém o arquivo `package.json` para restaurar os pacotes
- Execute `npm start` e em seguida vá para o seu navegador em [http://localhost:3000](http://localhost:3000) para visualizar a página acima

## Checklist Features
- Titles List
  - [X] - Campo para pesquisa não deve travar ao digitar termo de pesquisa
  - [x] - Deve desenhar mãos na tela e fazer com que elementos em segundo plano  continuem sendo clicáveis  🙌
  - [x] - Deve disparar scroll up quando usar a palma das mãos abertas 🖐
  - [x] - Deve disparar scroll down quando usar a palma das mãos fechadas ✊
  - [x] - Deve disparar click no elemento mais próximo quando usar  gesto de pinça 🤏🏻
  - [x] - Ao mover elementos na tela, deve disparar evento **:hover** em elementos em contexto

- Video Player
  - [X] - Deve ser possivel de reproduzir ou pausar videos com o piscar de olhos 😁
  - [X] - Todo processamento de Machine Learning deve ser feito via Web worker
  
### Créditos ao Layout
- Interface baseada no projeto [Streaming Service](https://codepen.io/Gunnarhawk/pen/vYJEwoM) de [gunnarhawk](https://github.com/Gunnarhawk)
