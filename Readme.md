# Otaku Development

[![Netlify Status](https://api.netlify.com/api/v1/badges/cf1161b6-a21d-4dd4-890b-a561ed3ef954/deploy-status)](https://app.netlify.com/sites/otaku-dev/deploys)

The website for [Otaku Development](https://otaku-dev.co.uk/), the Netlify version is [here](https://otaku-dev.netlify.app).

## 💁 tl:dr

- Clone Repo
- `cd` into repo
- `npm install`
- `npm run dev`

## 📝 Colophon
- [11ty](https://www.11ty.dev/) as a Static Site Generator
- [Nunjucks](https://mozilla.github.io/nunjucks/) for templating.
- [Webpack](https://webpack.js.org/)
- [PostCSS](https://postcss.org/)
- [postcss-preset-env](https://preset-env.cssdb.org/)
- [Highway](https://highway.js.org/) for page transitions

## 🚧 Development
The command `npm run dev` Does two things:

- Runs Webpack to compile and build all the static assets
- Runs a simple webserver with browser sync, as described in the [11ty Docs](https://www.11ty.dev/docs/usage/#re-run-eleventy-when-you-save)

Everything is serverd and hotreladed at [http://localhost:8080].

## 🏗 Build

`npm run build` will build the site and static assets into the `dist` folder.

## 🚀 Deployment
This site is hosted on [Netlify](https://netlify.com). It re-builds on every push of the `main` branch.
