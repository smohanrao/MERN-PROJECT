# User Management App.

Project is separated into:
- frontend application(React, Redux)
- api(NodeJS, express, MongoDB)

### How to run

1. Install live server: npm install -g live-server 
2. Install mongodb
3. Use correct version of node

Go to front folder and run:
```sh
$ npm install
$ npm run build
```

Go to dist folder and run:
```
$ live-server --entry-file=index.js //in next console tab
```

Go to api folder and run:
```sh
$ npm install
$ npm run dev
```

Or just type to open frontend and api part of project in separate terminal tabs at once:
```sh
$ ./start.sh
```
