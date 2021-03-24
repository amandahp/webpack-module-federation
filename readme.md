## O que é esse projeto?
Esse projeto é baseado no curso [Webpack do básico ao avançado + Projeto e Micro-frontend](https://www.udemy.com/course/webpack-do-basico-ao-avancado-com-projeto/). Dessa maneira, é criado uma aplicação formada por micro-frontends, através do [Module Federation](https://webpack.js.org/concepts/module-federation/).

## Como rodar a aplicação?
Para rodar a aplicação é necessário rodar os três aplicativos, ou seja, basta abrir as pastas: app; home e contact.
Basta utilizar o comando `npm run dev` em cada aplicação.

## Onde a aplicação está rodando?
A aplicação, consumindo as outras aplicações, estará rodando na porta: 
http://localhost:9001/

## Preview da aplicação:
![enter image description here](https://i.ibb.co/h7sswnG/Screenshot-from-2021-03-24-19-34-53.png)

Descrição: O cabeçalho está rodando na porta 9001; O Jumbutron está rodando na porta 9005; e a página de contato está rodando na porta 9007.
