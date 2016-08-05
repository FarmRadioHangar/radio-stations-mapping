# radio-stations-mapping

To build the project, you need to have [npm](https://www.npmjs.com/) and [Node](https://nodejs.org/) installed.

## Project setup

```
npm install
npm install webpack -g
```

(The second command may need to be run as root.)

### Webpack dev server (optional)

As root:

```
npm install webpack-dev-server -g
```

To start the dev server, type `webpack-dev-server --progress --colors`. Point your browser to `http://localhost:8080/public/`.

If port `8080` is already in use on the host system, specify an alternative port by appending, e.g., `--port 8081` to the command.

## Build command

```
webpack
```

