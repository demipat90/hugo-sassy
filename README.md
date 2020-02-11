# Hugo Sassy Theme

[![Hugo](https://img.shields.io/badge/hugo-0.43-blue.svg)](https://gohugo.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

### [Sass](https://sass-lang.com/) integrated Hugo skeleton theme

## Requirements

- Hugo 0.43 or higher
- Hugo extended version, read more [here](https://gohugo.io/news/0.43-relnotes/)

## Installation

Navigate to your hugo project root and run:

```
git submodule add https://github.com/demipat90/hugo-sassy.git themes/sassy
```

Then run hugo (or set `theme = "sassy"`/`theme: sassy` in configuration file)

```
hugo server --theme sassy
```

### Updating

From the root of your site:

```sh
git submodule update --remote --merge
```

### Run example site

From the root of themes/zzo/exampleSite:

```sh
hugo server --themesDir ../..
```

### Creating site from scratch

Below is example how to create new site from scratch

```sh
hugo new site mysite; cd mysite
git init
git submodule add https://github.com/demipat90/hugo-sassy.git themes/sassy
cp -R themes/sassy/exampleSite/content .
```

```sh
hugo server --theme sassy
```
