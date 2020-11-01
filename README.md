<h1 align="center">
  BootStrap Web Starter
</h1>

<h3 align="center">Template from <a href="https://github.com/twbs/bootstrap-npm-starter">Boostrap NPM Starter</a> </h3>

<p align="center">Start your NPM website faster using this customized templates</p>

## About

`Bootstrap Web Starter` is a node website starter with bootstrap installed and local server. 

[![Build Status](https://github.com/ChrisAchinga/Bootstrap-Starter/workflows/CI/badge.svg)](https://github.com/ChrisAchinga/Bootstrap-Starter/actions)

[![Netlify Status](https://api.netlify.com/api/v1/badges/f48cb63c-4fcc-47cf-983b-45771cb8b25a/deploy-status)](https://app.netlify.com/sites/webstarternode/deploys)

## Using This Template Directly

To start using this template, click the `Use This Template` green button at the top right. Or Use this link:

[Use Template](https://github.com/ChrisAchinga/Bootstrap-Starter/generate)

Read More in the Wiki


## Starting Your Project

How you'll use the templates

## Running Your Web

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

## Actions CI

We've included some simple GitHub Actions in this template repo. When you generate your new project from here, you'll have the same tests that run whenever a pull request is created. We've included Actions for the following:

- Stylelint for your CSS

When your repository is generated, you won't see anything in the Actions tab until you create a new pull request. You can customize these Actions, add new ones, or remove them outright if you wish.

[Learn more about GitHub Actions](https://github.com/features/actions), [read the Actions docs](https://help.github.com/en/actions), or [browse the Actions Marketplace](https://github.com/marketplace/actions).


### Special Thanks To

- @mdo 2020 and licensed MIT.
