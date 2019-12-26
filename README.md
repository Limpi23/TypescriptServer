# TypescriptServer
configure server with typescript

### FIRST TypeScript installed as a global

```sh
$ npm i -g typescript
```

### SECOND create typescript project

```sh
$ cd folderProject
$ npm init -y
$ tsc --init
```

### THIRD create the following structure
```sh
$ mkdir src dist src/routes src/controllers src/config
$ touch src/index.ts src/config/constants.ts
```

### install the following dependencies

```sh
$ npm i express
$ npm i -D concurrently nodemon @types/express
```
