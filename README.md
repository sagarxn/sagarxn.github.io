# Portfolio

[![GitHub Pages Deployment](https://img.shields.io/github/actions/workflow/status/sagarxn/sagarxn.github.io/pages.yml?label=Deployment&logo=github&style=flat-square)](https://github.com/sagarxn/sagarxn.github.io/actions/workflows/pages.yml)
[![Website](https://img.shields.io/website-up-down-green-red/https/sagarchaudhary.info.np.svg?label=Website&logo=google-chrome&style=flat-square)](https://sagarchaudhary.info.np)


## About
This is the source code for my personal portfolio website hosted on GitHub Pages.

## Dependencies
This project requires [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/).

### 1. Hexo
Hexo is used as the static site generator. You can install the Hexo CLI globally (recommended):
```sh
npm install -g hexo-cli
```

### 2. Theme
This project uses a modified version of the [Cactus theme](https://github.com/probberechts/hexo-theme-cactus). The theme source is included directly in this repository.

## Getting Started

### 1. Clone the repository
Clone the repository recursively to include the theme submodule:
```sh
git clone https://github.com/sagarxn/sagarxn.github.io.git
cd sagarxn.github.io
```

### 2. Install dependencies
Install the required npm packages:
```sh
npm install
```

### 3. Generate static files
Generate the `public` folder:
```sh
hexo generate
```

### 4. Run locally
Start a local server to preview your changes:
```sh
hexo server -p 8000
```
The site will be available at `http://localhost:8000`.

## Deployment
This portfolio is automatically deployed to GitHub Pages using a GitHub Actions workflow. The custom domain `sagarchaudhary.info.np` is configured via a `CNAME` file.

## Live Website
Visit the live website here: [https://sagarchaudhary.info.np](https://sagarchaudhary.info.np)

## License

This project is released under a dual-license structure.

- The **source code** of this website, including the theme and any customizations, is licensed under the [MIT License](LICENSE).
- The **content**, including all text and images created by Sagar Chaudhary, is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

For more details, please see the [LICENSE](LICENSE) file.
