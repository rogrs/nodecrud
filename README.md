# nodecrud 
[![Build Status](https://travis-ci.org/rogrs/app-nodecrud.svg?branch=master)](https://travis-ci.org/rogrs/nodecrud)
 [![Dependency Status](https://david-dm.org/rogrs/nodecrud.svg)](https://david-dm.org/rogrs/nodecrud) 
[![devDependency Status](https://david-dm.org/rogrs/nodecrud/dev-status.svg)](https://david-dm.org/rogrs/nodecrud#info=devDependencies) 
[![peerDependency Status](https://david-dm.org/rogrs/nodecrud/peer-status.svg)](https://david-dm.org/rogrs/nodecrud#info=peerDependencies)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

> Projeto de Crud utilizando node.js e My SQL.



## Instalação
*Baixe ou clone o projeto do repositorio, depois execute o comando abaixo :

	npm install

## Configuração (database)
Para configurar o banco de dados  edite o arquivo app.js

        host: 'localhost',
        user: 'root',
        password : 'root',
        port : 3306, //port mysql
        database:'nodejs'	


Crie o banco de dados  com o nome de 'nodejs' e  importe o script data.sql



## Para executar aplicação 
        
        node app.js

## License

Code is under the [Apache Licence v2](https://www.apache.org/licenses/LICENSE-2.0.txt).
