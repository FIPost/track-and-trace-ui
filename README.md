![ipost-logo](https://github.com/FIPost/docs/blob/master/assets/logo-name.png?raw=true)

# Track & Trace User Interface
<h3 align="center">
  <a href="https://github.com/FIPost/docs">Documentation</a>
</h3>

VueJS front-end for viewing package statusses.

## Getting Started
Install node modules.
```zsh
npm install
```

Serve VueJS
```zsh
npm run serve
```

## Getting Started with Docker
The docker image used in this build uses a Nginx webserver to serve the SPA VueJS content.

```zsh
docker build -t t-t-ui .
docker run -p 5002:5002 t-t-app t-t-ui
```
