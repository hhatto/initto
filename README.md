# Tech Blog based on Eleventy

blog kit with [11ty(Eleventy)](https://11ty.io) based on [hylia-forestry](https://github.com/DirtyF/hylia-forestry).

## Prepare your own environment

### installation
Please execute it when installing in your environment for the first time. Not needed if already running

```bash
$ npm ci
```

### serve on local
Please execute when starting the system in your environment

```bash
$ npm start
```

### Build a production version of the site
The production version is set automatically, so you don't have to run it.

```bash
$ npm production
```

## How to write article

### Article in English

Create a new md file in `src/posts`
e.g.: `sample.md`

### Article in Japanese

Create a new md file in `src/ja/post`
e.g.: `sample.md`

### Contents
The contents of the article file are as follows

```
---
title: <title>
date: <publish date>
tags:
- <tags...>
- <tags...>
- <tags...>
---
<contents>
```

The text enclosed in `---` is the meta information of the article.
Please write the title, date, tag, etc. of the article.
Please write the body of the article from below the meta information.
Write the article in markdown format