# Concourse CI Editor (Forked from Swagger Editor)

[![Screenshot of the Swagger Editor](docs/screenshot.png "Designing an API with the Swagger Editor")](http://editor.swagger.io)

#### Running with Docker

The swagger-editor is published in a [public repository on Dockerhub](https://hub.docker.com/r/swaggerapi/swagger-editor/)

You can run editor easily with docker:

```bash
docker pull swaggerapi/swagger-editor
docker run -p 80:8080 swaggerapi/swagger-editor
```

#### Running Locally

[**Download the latest release (v2.10.4)**](https://github.com/swagger-api/swagger-editor/releases/download/v2.10.4/swagger-editor.zip) and serve the static files via your HTTP server. If you don't have an HTTP server, you can use [`http-server`](https://www.npmjs.com/package/http-server) Node.js module.

###### Using `http-server` module:
```shell
npm install -g http-server
wget https://github.com/swagger-api/swagger-editor/releases/download/v2.10.4/swagger-editor.zip
unzip swagger-editor.zip
http-server swagger-editor
```

#### Building From Source

Make sure you have [Node.js](http://nodejs.org/) installed. 

```shell
git clone https://github.com/swagger-api/swagger-editor.git
cd swagger-editor
npm install
npm start
```

#### Documentations
* [Importing your Swagger document](./docs/import.md)
* [Development Guide](./docs/development.md)
* [Configuration Guide](./docs/config.md)
* [Cross Origin Request Sharing(CORS) issues](docs/cors.md)

[Contributing](./.github/CONTRIBUTING.md)

[LICENSE](./LICENSE)

---
<img src="http://swagger.io/wp-content/uploads/2016/02/logo.jpg"/>
