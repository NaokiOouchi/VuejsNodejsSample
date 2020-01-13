# VuejsNodejsSample
## Vue.js + Node.js StandardProject Sampple

## 構築
### frontend
```
cd ./VuejsNodejsSample
```
```
vue init webpack front_vue
cd  front_vue
npm run dev
```
access to http://localhost:8080/
### backend
```
mkdir backend
cd backend/
npm init
npm install --save nodemon express body-parser cors
```

edit package.json
```
  "scripts": {
    "start": "./node_modules/nodemon/bin/nodemon.js index.js"
  },
```
```
touch index.js
```
edited index.js
```
npm start
```
access to http://localhost:3000/test

## 概要
frontend  
```
src/api
httpリクエストを投げるための処理を記載しています。

components
HelloWordl.vue
入力フォームの値をバックエンドに投げ、返却値を出力する処理を記載しています。
```

backend  
```
index.js
入力値をそのまま返却する処理を記載しています。
```
