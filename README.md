# Fredrin scratch

A scratch project created with [Fredrin](https://fredrin.com), used for trying
out tickets and Workers. It has no application code yet: the repository holds
only this README, [`AGENTS.md`](AGENTS.md) (conventions for AI coding agents)
and a `.gitignore`.

## Install

Nothing needs installing. Clone or open the repository and you're done:

```sh
git clone <path-to-fredrin-scratch>
cd fredrin-scratch
```

The project runs on local git. It has no remote and doesn't need one, since
branches, worktrees, diffs and merges all happen locally.

## Run locally

There's nothing to run yet, because the project has no build, test or start
commands. When code lands, add its commands here and in the **Commands**
section of [`AGENTS.md`](AGENTS.md).

## Layout

| Path         | What it is                                                       |
| ------------ | ---------------------------------------------------------------- |
| `README.md`  | This file.                                                       |
| `AGENTS.md`  | Instructions for AI coding agents. It's a stub for now.          |
| `.gitignore` | Ignores dependencies, secrets, build output and editor files.    |
| `.fredrin/`  | Fredrin's machine-local tool state. It's ignored and never committed. |
