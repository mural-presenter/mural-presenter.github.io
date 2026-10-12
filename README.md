# MURAL Presenter — Project website

Official project website: **https://mural-presenter.github.io/**

- [English](https://mural-presenter.github.io/) / [中文](https://mural-presenter.github.io/zh/)
- [Benchmark Arena](https://mural-presenter.github.io/arena/)
- [Research paper](https://mural-presenter.github.io/paper/)
- [Project source code](https://github.com/G1nkgo7/MURAL-Presenter)

This repository hosts the generated static website, including bilingual pages, browser interactions, presentation galleries, and paper assets. GitHub Pages publishes the root of `main`; `.nojekyll` preserves the prebuilt assets.

Website changes are made in the maintained site source and exported with:

```sh
npm run build:pages -- --site-url https://mural-presenter.github.io/
```

Sync the resulting `out/` contents into this repository, then commit and push to `main`.
