#

### Instalación de React y React DOM
1. Utilizamos el comando para crear inicializar el proyecto y crear package.json: npm init
// colocamos datos relevantes al momento de inicializar con git
// name: react-shop
// description: react-eshop
// entry point: src/index.js
// author: nombre <correo>
// license: MIT 

2. Instalamos las dependencias de react
npm intall react react-dom

3. Creamos la carpeta src/public // Donde se guardaran los elementos públicos al mandar a producción la app
 y la carpeta components/

4. Creamos los archivos index.html en public/ y index.js en src/

5. Creamos nuestra app en components/ como app.jsx
importamos react - shortcut: imr
crear stataless component - shortcut: slr

6. creamos primera parte: 
import React from 'react'

const App = () => {
    return(
        <h1>Store</h1>
    );
}

export default App;

7. Agregamos la app en nuestro js
import React from 'react';
import ReactDOM from 'react-dom';

ReactDOM.render(<App />, document.getElementById('app'));

8. Agregamos la configuración personalizada diferente a create react app con:  
Comandos NPM

Babel:

 npm install @babel/core @babel/preset-env @babel/preset-react 
Webpack:

npm install webpack webpack-cli webpack-dev-server 
HTML plugin:

 npm install babel-loader html-loader html-webpack-plugin

 9. Creamos el archivo .babelrc donde vamos a guardar los preset que instalamos anteriormente
 {
    "presets": [
        "@babel/preset-env", 
        "@babel/preset-react" 
    ]
}

10. creamos webpack.config.js que nos permitirar personalizar nuestro proyecto y agregamos la vista al virtual dom en index.js

11. Agregamos estilos sass y agregamos en terminal lo siguiente:

npm install css-loader
npm install  -g sass
npm i mini-css-extract-plugin
npm install style-loader --save

12. 

npm install babel-preset-es2015


