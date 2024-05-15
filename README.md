# astro-gfio-sessions

> A workshop project with Astro, Shoelace and Lit

## Objectives

| _task_ | _status_ |
| --- | --- |
| Develop scripts that fetch the [gongfu dev sessions historical data](https://github.com/gongfudev/sessions/issues) | done |
| Create Astro components that display the fetched data | done |
| Publish this project on [netlify](https://astro-gfio-sessions.netlify.app/) | done |
| Publish this project on [vercel](https://astro-gfio-sessions.vercel.app/) | done |
| Develop scripts and components for creation and publishing future gongfu dev sessions data | - |
| Transfer scripts and components to the [gongfu dev website](https://github.com/gongfudev/website) project| - |

## 🚀 Quick start

To run the project locally, follow these steps:

```sh
  % npm run fetch # fetch the gongfu dev sessions data and save it to src/data/

  % npm run dev

  % npm run build
  % npm run preview
```

Open the page [localhost:4321](http://localhost:4321/)

For a quick look at fetched data you can run the fetch script as

```sh
  % scripts/fetch-gfio-sessions-data.js
```

NOTE: make sure that you have a local `.env` file containing a valid github access token (otherwise your fetch operation will be rate limited)

```sh
  GITHUB_ACCESS_TOKEN=ghp_...
```

<h2>Published!</h2>

Now (07.05.2024) the project is published on [netlify](https://astro-gfio-sessions.netlify.app/).

## Project history

> This project was created from [‹new-astro-repo›](https://github.com/gongfudev/new-astro-repo) as template

Starter project with Astro, Shoelace and Lit.

## Status

👾 Tinkering. Work-in-progress.

## Components

|Component|Description|
|---|---|
|[`‹TODO›`](TODO)|Description of the `‹TODO›` component|

## 🚀 Project Structure

The source code of the layouts lives in the [`src/pages/`](src/pages/) subfolder.

At its root, this repository is an [Astro](https://astro.build) publication, that is automatically published by Vercel on commits, to allow browsing the layout templates online.

You can preview the Astro publication by running `npm start` after installing the deps. The publication was generated by running the following command:

```sh
npm create astro@latest -- --template basics
```

Inside of the Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 📚 Learn more about Astro

Check the [documentation of Astro](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## License

Distributed under the Apache-2.0 license. See [LICENSE](LICENSE) for details.
