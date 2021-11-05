# P5.js Typescript Skeleton Project

Quickly get up and running with a [p5.js](https://p5js.org/) typescript project.

## Quick Start

Clone this project, and re-initialize it for your project.

```bash
git clone https://github.com/justino/p5ts-skeleton <project name>
cd <project name>
rm -rf .git
git init .
git add .
git commit -m 'Initial Setup'
npm install
npm start
```

## Access

You can access the development server via [http://localhost:1234/](http://localhost:1234/)

## Build

You can simply build your project with:

```bash
npm run build
```

Build artifacts are created in the `dist` subdirectory.

## Tech

Makes use of the [Parcel](https://parceljs.org/) build system.

Pre-configured with [Sass](https://sass-lang.com/) support.

Pre-configured with [Normalize.css](https://necolas.github.io/normalize.css/).

## Optional Tech

Supports VSCode [Devcontainers](https://code.visualstudio.com/docs/remote/containers) with a handful of pre-configured VSCode extensions.
Modify `./devcontainer/devcontainer.json` with your project name so that the container name makes sense.

Supports [Editorconfig](https://editorconfig.org/) with some basic settings.

## Notes

p5.js will run in [instance mode](https://github.com/processing/p5.js/wiki/Global-and-instance-mode) only. No cluttering of the global space.

## License

MIT License, see [LICENSE](https://github.com/justino/p5ts-skeleton/blob/master/LICENSE) for details.
