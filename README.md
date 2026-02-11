# Portfolio

[![GitHub Pages Deployment](https://img.shields.io/github/actions/workflow/status/sagarxn/sagarxn.github.io/pages.yml?label=Deployment&logo=github&style=flat-square)](https://github.com/sagarxn/sagarxn.github.io/actions/workflows/pages.yml)
[![Website](https://img.shields.io/website-up-down-green-red/https/sagarchaudhary.info.np.svg?label=Website&logo=google-chrome&style=flat-square)](https://sagarchaudhary.info.np)


## About
This is the source code for my personal portfolio website hosted on GitHub Pages.

## Dependencies

### 1. HEXO
Install `HEXO` and its dependencies from the [official webpage](https://hexo.io/docs/).

### 2. HEXO Theme Cactus
Check the [HEXO Theme Cactus](https://themes.gohugo.io/themes/hugo-profile/).

## Start

### 1. Clone the repository recursively.
```sh
git clone git@github.com:sagarxn/sagarxn.github.io.git --recursive
cd sagarxn.github.io.git
# cd themes/cactus
# git checkout 7a6074d
```

### 2. Generate static files.
```sh
hexo generate
```

### 2. Deploy on a local server.
```sh
hexo server -p 8000
```

## Deployment
This portfolio is automatically deployed to GitHub Pages using a GitHub Actions workflow. The custom domain `sagarchaudhary.info.np` is configured via a `CNAME` file.

## Live Website
Visit the live website here: [https://sagarchaudhary.info.np](https://sagarchaudhary.info.np)
