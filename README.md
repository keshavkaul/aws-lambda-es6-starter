### AWS lambda node es6 starter template
This is a starter template for writing es6 javascript lambda code targeting `node 6.10` runtime engine.

### Usage
1. Clone this repo.
2. Run `yarn install`.
3. Write es6 modules in `src` folder.
4. Write lambda handler logic inside `handler()` function in `src/index.js`.
5. Add any runtime dependencies into `bundledDependencies` array in `package.json`.
5. Run `npm run build` to transpile es6 js into aws node js. Output folder is `bin/`.
6. Run `npm run pack2zip` to perform `npm pack` and convert `*.tgz` to `*.zip`.
7. upload the created zip file to aws lambda.
8. Configure the handler name to be `package/bin/index.handler`.

## License
[MIT](./LICENSE)
