# AGENTS.md

Conventions for AI coding agents working in **Fredrin scratch**. This file is the
canonical entry point under the [AGENTS.md](https://agents.md) standard, and it
is the first thing a Fredrin Worker reads.

## Project

A static About Me page for John Pritchard, AI infrastructure engineer. The whole
site is `index.html`: semantic HTML with inline CSS, no JavaScript and no
external assets.

## Commands

- **Run:** open `index.html` in a browser.
- **Build / test:** none. There are no dependencies and no build step.

## Conventions

- The page copy comes from the human and is the source of truth. Don't reword
  it, and preserve every figure exactly.
- Links without a real URL use `#todo-<name>-url` placeholder anchors. Never
  invent a URL for them.
- Keep the page dependency-free: no frameworks, web fonts or CDN assets.
