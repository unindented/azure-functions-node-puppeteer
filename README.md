# Azure Functions - Node + Puppeteer

[![Image information](https://images.microbadger.com/badges/image/unindented/azure-functions-node-puppeteer.svg)](https://microbadger.com/images/unindented/azure-functions-node-puppeteer) [![Version information](https://images.microbadger.com/badges/version/unindented/azure-functions-node-puppeteer.svg)](https://microbadger.com/images/unindented/azure-functions-node-puppeteer)

## Usage

Create a `Dockerfile` with the following content:

```
FROM unindented/azure-functions-node-puppeteer:latest

COPY . /home/site/wwwroot
```

Build your image:

```
docker build -t your-image .
```

And then run it:

```
docker run --rm -it -p 8080:80/tcp your-image
```

## Meta

- Code: `git clone https://github.com/unindented/azure-functions-node-puppeteer.git`
- Home: <https://github.com/unindented/azure-functions-node-puppeteer>

## Contributors

Daniel Perez Alvarez ([unindented@gmail.com](mailto:unindented@gmail.com))

## License

Copyright (c) 2019 Daniel Perez Alvarez ([unindented.org](https://unindented.org/)). This is free software, and may be redistributed under the terms specified in the LICENSE file.
