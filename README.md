# Fredrin scratch

A scratch project created with [Fredrin](https://fredrin.com), used for trying
out tickets and Workers. It holds a single static page, `index.html`: an About
Me page for John Pritchard, written in plain HTML and CSS with no build step.

**[View the About Me page →](https://jhpritch-dev.github.io/fredrin-scratch/)**
It's published with GitHub Pages from `index.html` on `main`.

## Install

Nothing needs installing. Clone or open the repository and you're done:

```sh
git clone https://github.com/jhpritch-dev/fredrin-scratch.git
cd fredrin-scratch
```

## Run locally

Open `index.html` in a browser. There's nothing to install, build or serve:
the page has no dependencies, scripts or external assets.

## Publish

GitHub Pages serves the root of `main` at
<https://jhpritch-dev.github.io/fredrin-scratch/>. Merging to `main` republishes
the page within a minute or two; there's no separate deploy step.

## Layout

| Path         | What it is                                                       |
| ------------ | ---------------------------------------------------------------- |
| `index.html` | The About Me page: markup and inline CSS in one file.            |
| `README.md`  | This file.                                                       |
| `AGENTS.md`  | Instructions for AI coding agents.                               |
| `.gitignore` | Ignores dependencies, secrets, build output and editor files.    |
| `.fredrin/`  | Fredrin's machine-local tool state. It's ignored and never committed. |
