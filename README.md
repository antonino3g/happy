<h1 align="center">
    <img alt="Happy" title="Happy" src="https://i.ibb.co/kJ07NzL/logo.png" />
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-anotações">Anotações</a>&nbsp;&nbsp;&nbsp;

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/apfjunior/happy">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/apfjunior/happy">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/apfjunior/happy">
  <a href="https://github.com/apfjunior">
    <img alt="Made by Antonino Praxedes" src="https://img.shields.io/badge/created%20by-Antonino%20Praxedes-blue">
  </a>
</p>

<br>

<p align="center">
  <img alt="Happy" src="https://i.ibb.co/prNgs72/happy.png" width="100%">
</p>

## 🚀 Tecnologias
Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Axios](https://github.com/axios/axios)
- [Cors](https://github.com/expressjs/cors)
- [Express](https://expressjs.com/)
- [Expo](https://expo.io/)

## 💻 Projeto
O Happy é uma aplicação que conecta pessoas à casas de acolhimento institucional para fazer o dia de muitas crianças mais feliz. Feito na semana Next Level Week #3 da RocketSeat.

## 🔖 Anotações 
```bash
## Day 01

# Install react-icons
$ yarn add react-icons

# Install react-router-dom
$ yarn add react-router-dom
$ yarn add @types/react-router-dom -D

## Maps

# Install leaflet react-leaflet
$ yarn add  leaflet react-leaflet
$ yarn add @types/react-leaflet - D

```
---
```bash
## Day 02

BACKEND

$ yarn add express
$ yarn add @types/express -D
$ yarn add typescript -D

# Init Typescript
$ yarn tsc --init

# Editing tsconfig.json file
"target": "es5" to "target": "es2017",   

$ yarn add ts-node-dev -D

# Adding in package.json :

 "scripts": {
    "dev": "ts-node-dev --transpile-only --ignore-watch node_modules src/server.ts",
    "typeorm": "ts-node-dev ./node_modules/typeorm/cli.js"
  },
  
# Database
$ yarn add typeorm sqlite3

# Adding ormconfig.json
{
  "type": "sqlite",
  "database": "./src/database/database.sqlite",
  "migrations": [
    "./src/database/migrations/*.ts"
  ],
  "cli": {
    "migrationsDir": "./src/database/migrations"
  }
}

tsconfig.json
   "strictPropertyInitialization": false,
    "experimentalDecorators": true,        
    "emitDecoratorMetadata": true, 
    

# Install upload images MULTER
$ yarn add multer
$ yarn add @types/multer -D 

# Install express-async-errors
$ yarn add express-async-errors

# Install yup
$ yarn add yup
$ $ yarn add @types/yup -D

# Install cors
$ yarn add cors
$ yarn add @types/cors -D

```
---
```bash

## Day 3

# Instal axios
$ yarn add axios
```
---
```bash

## Day 4

$ yarn global add expo-cli

# Testing expo
# expo -h

# Init expo
$ expo init mobile

# Install maps in Expo
$ expo install react-native-maps

# Create a folder "@types" && create a file "index.d.ts. Content:
declare module "*.png";

# Install google-fonts nunito by Expo
$ expo install @expo-google-fonts/nunito expo-font

# Install react-navigation
$ yarn add @react-navigation/native  

# Installing dependencies into an Expo managed project
$ expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

# Install react-navigation-stack
$ yarn add @react-navigation/stack
```
---
```bash
## Day 5 

# Install axios
$ yarn add axios

# Using IP Adress as localhost Android Emulator. ON Terminal
$ adb reverse tcp:3333 tcp:33333

# IOS Emulator
## Put localhost normal

# Expo Device
## Get IP Adress on tab Expo Browser

# Install expo module images picker
$ expo install expo-image-picker
```
