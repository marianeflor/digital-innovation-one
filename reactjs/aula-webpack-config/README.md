# Notas da aula

## Comandos npm

- npm init -y
- npm i --save-dev webpack webpack-cli
- npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
- npm i react react-dom
- npm i --save-dev babel-preset-react
- npm i --save-dev webpack-dev-server

## package.json

"scripts": {
"build": "webpack --mode poduction",
"dev": "webpack --mode development",
"start:dev": "webpack-dev-server"
},

## .babelrc

{
"presets": [
"@babel/preset-env",
"@babel/preset-react",
]
}
