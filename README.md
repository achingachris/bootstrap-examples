<h1 align="center">
  BootStrap Examples
</h1>

<h3 align="center">Template from <a href="https://github.com/twbs/bootstrap-npm-starter">Boostrap NPM Starter</a> </h3>

![CI](https://github.com/ChrisAchinga/bootstrap-examples/workflows/CI/badge.svg)

<p align="center">Start your NPM website faster using this customized templates</p>

## About

Bootstrap Examples


## Running The Project

Be sure to have [Node.js](https://nodejs.org/) installed before proceeding.

```shell
# Clone the repo
git clone https://github.com/twbs/bootstrap-npm-starter
cd bootstrap-npm-starter

# Install dependencies
npm i

# Compile Sass
npm run css-compile

# Watch Sass for changes (uses nodemon)
npm run watch

# Start local server (uses serve)
npm start
```

For the most straightforward development, open two Terminal tabs to execute `npm run server` and `npm run watch` at the same time.

Open <http://localhost:3000> to see the page in action.

## Scripts

The following npm scripts are available to you in this starter repo. With the exception of `npm start`, the remaining scripts can be run from your command line with `npm run scriptName`.

| Script | Description |
| --- | --- |
| `server` | Starts a local server (<http://localhost:3000>) for development |
| `watch` | Automatically recompiles CSS as it watches the `scss` directory for changes |
| `css` | Runs `css-compile` and `css-prefix` |
| `css-compile` | Compiles source Sass into CSS |
| `css-prefix` | Runs Autoprefixer on the compiled CSS |
| `css-purge` | Runs PurgeCSS to remove CSS that is unused by `index.html` |
