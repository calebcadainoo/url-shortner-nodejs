# Commands For Project

### 1. Initialize Node
```sh
npm init
```

### 2. Install Packages: Express, Mongoose(for Mongo DB) and EJS(for views)
```sh
npm i express mongoose ejs
```

### 3. Install Nodemon(for auto refresh of server)
```sh
npm i --save-dev nodemon
```

### 4. Modify the package.json file
change from
```sh
"test": "echo \"Error: no test specified\" && exit 1"
```
to
```sh
"devStart": "nodemon server.js"
```
