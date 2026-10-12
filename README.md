# Fredrin scratch

A scratch project created with [Fredrin](https://fredrin.com), used for trying
out tickets and Workers. It holds a single static page, `index.html`: an About
Me page for John Pritchard, written in plain HTML and CSS with no build step.

## Install

Nothing needs installing. Clone or open the repository and you're done:

```sh
git clone <path-to-fredrin-scratch>
cd fredrin-scratch
```

The project runs on local git. It has no remote and doesn't need one, since
branches, worktrees, diffs and merges all happen locally.

## Run locally

Open `index.html` in a browser. There's nothing to install, build or serve:
the page has no dependencies, scripts or external assets.

Links whose URLs haven't been supplied yet point at `#todo-…` placeholder
anchors. Search `index.html` for `#todo-` to fill them in.

## Layout

| Path         | What it is                                                       |
| ------------ | ---------------------------------------------------------------- |
| `index.html` | The About Me page: markup and inline CSS in one file.            |
| `README.md`  | This file.                                                       |
| `AGENTS.md`  | Instructions for AI coding agents.                               |
| `.gitignore` | Ignores dependencies, secrets, build output and editor files.    |
| `.fredrin/`  | Fredrin's machine-local tool state. It's ignored and never committed. |
