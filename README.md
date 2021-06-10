# NodeJs-Template

Plantilla de NodeJS para empezar proyectos rápidamente [Express 4](http://expressjs.com/).

Esta aplicacion soporta [Getting Started with Node on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Ejecución en local

Asegurate de que tienes [Node.js](http://nodejs.org/) y [Heroku CLI](https://cli.heroku.com/) instalado.

```sh
$ git clone git@github.com:jomaoppa/node-js-template.git # or clone your own fork
$ cd node-js-template
$ npm install
$ npm start
```

Tu aplicación debe estar ejecutandose en [localhost:5000](http://localhost:5000/).

## Desplegando en Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
o

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

