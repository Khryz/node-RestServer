1.- Instalar mongoDB
	https://docs.mongodb.com/master/tutorial/install-mongodb-on-windows-unattended/
2..- Instalar Robo3T
	https://robomongo.org/download
3.- Tener corriendo mongod.exe
4.- ir a buscar en internet npm express
5.- En la carpeta principal:
	npm init
	npm install express --save
6.- Crear carpeta server
	/server.js
	pegar codigo de express
7.- instalar npm bodyparser
	npm i body-parser --save
8.- Pegar codigo de npm bodyparser 
	var bodyParser = require('body-parser')
9.- Pegar las 2 lineas de body parser de x-www abajo de lo anterior
	// parse application/x-www-form-urlencoded
	app.use(bodyParser.urlencoded({ extended: false }))
 
	// parse application/json
	app.use(bodyParser.json())