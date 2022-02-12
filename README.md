# Weather client

Sample React web app written in Typescript. Consumes the [weather-server](https://github.com/capelski/weather-server) web Api and displays the returned weather data. Once built, it can be served by `weather-server` by copying the generated files to the server's `public` folder.

```bash
# 1) Install dependencies
npm install

# 2) Build and start or start in development mode
npm run build && npm start
npm run start:dev
```

## Motivation

The goal of this repository is to illustrate different ways of structuring interdependent Typescript projects. See [weather-monorepo](https://github.com/capelski/weather-monorepo) for more details.
