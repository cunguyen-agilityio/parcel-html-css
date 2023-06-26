# HTML/CSS with Parcel

Create and build a base app for HTML/CSS with Parcel. Parcel is a zero configuration build tool for the web. It combines a great out-of-the-box development experience with a scalable architecture that can take your project from just getting started to massive production application. View more about [Parcel](https://parceljs.org/).

Author: Cu Nguyen &lt;[cu.nguyen@asnet.com.vn](cu.nguyen@asnet.com.vn)&gt;

Deploy to Netlify: [https://parcel-html-css.cunguyen.com/](https://parcel-html-css.cunguyen.com/)

## Targets

- This help to guide those who are starting with HTML/CSS and has an overview of a base web structure
- Quick start with HTML/CSS with a build tool that supports hot reload, minimizes the code, transfers JavaScript, JSX, and TypeScript

## Requirements

- [Node](https://nodejs.org/en/) &gt;=8.4.0 / [npm](https://www.npmjs.com/) &gt;=5.3.0
  - You can install via [nvm](https://github.com/creationix/nvm)
- [Yarn](https://classic.yarnpkg.com) (Optional) &gt;=1.22.4

## File & folder structure

```
├── .gitignore
├── package.json
├── yarn.lock
├── README.md
└── src
    ├── favicon.ico
    └── assets
        ├── audios
        ├── videos
        └── images
    ├── pages
        ├── index.html
        └── 404.html
    ├── scripts
        └── index.js
    └── styles
        └── main.css
```

## Getting Started

Step by step to run this app in your local

### Install packages

At your directory root, run:

```bash
npm/yarn install
```

### Run server

```bash
npm/yarn start
```

### Build

```bash
npm/yarn run build
```

## Some notes

- You can update the source structures to follow your patterns.
- Parcel v2 has supported the autoprefixer plugin without any config, in case you want to custom more oldest browsers, you can define it in the `package.json` [(View document)](https://parceljs.org/features/targets/#package.json%23browserslist)
- Live reload is supported on this repository
- Web default port is `http://localhost:1234`, you can custom it
