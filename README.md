yarn init -y

yarn add express

yarn add @types/express -D

yarn add typescript -D

yarn tsc --init

tsconfig.json -> "outDir": "./dist",

yarn add eslint -D

yarn eslint --init

yarn add -D eslint-plugin-import-helpers eslint-import-resolver-typescript

.eslintignore ->
/*.js
node_modules
dist

yarn add prettier eslint-config-prettier eslint-plugin-prettier -D

yarn add ts-node-dev -D

"scripts": {
"dev": "ts-node-dev --transpile-only --ignore-watch node_modules --respawn src/server.ts"
},

