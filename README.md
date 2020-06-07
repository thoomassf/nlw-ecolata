# Ecoleta-NLW

## Ecoleta - Next Level Week

> Projeto desenvolvido em 5 dias, na semana Next Level Week pelo Rocketset

## Tecnológias utlizadas:

* HTML
* CSS
* JavaScript

## Requisitos para a aplicação:

* Express
* Nunjucks
* Sqlite3
* nodemon

## passo a passo para instalar os requisitos no projeto:

* Iniciar arquvio json: npm init -y

* Instalar o express para a dependencias do node: npm install express

* Iniciar o servidor: node src/server.js

* Para o servidor sempre iniciar automaticamente: npm install nodemon -D

* Instale para poder usar variaveis e funções no HTML: npm install nunjucks

* Aperte CTRL + P e acesse os "Open Settings (JSON)" para configurar o nunjucks no vscode:
    
    "files.associations": {
        "*.html": "njk"
    },
    "emmet.includeLanguages": {
        "njk": "html"
    },
    "vsicons.associations.files": [
        { "icon": "nunjucks", "extensions": ["html"], "format": "svg" }
    ],
    "workbeanch.iconTheme": "vscode"

* Instalar o SQLite3: npm install sqlite3