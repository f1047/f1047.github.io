# f1047.github.io

Personal landing page built with Astro.

## Project Structure

```text
/
├── public/
│   ├── favicon.ico
│   ├── favicon.svg
│   └── landing-background.png
├── src
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       ├── index.astro
│       └── privacy-policy.astro
└── package.json
```

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Installs dependencies                            |
| `bun dev`                 | Starts local dev server at `localhost:4321`      |
| `bun build`               | Builds the production site to `./dist/`          |
| `bun preview`             | Previews the build locally                       |
| `bun astro ...`           | Runs Astro CLI commands                          |
