# KBase CSS

Based on [Tachyons](http://tachyons.io/), using the same classnames. Refer to its documentation for usage.

This video has a succinct explanation of how this repo was set up: https://vimeo.com/174698456

## Installation

> WIP

Using the unpkg cdn:

```
<link rel="stylesheet" href="https://unpkg.com/kbaseincubator/kbase-css@4.11.2/css/tachyons.min.css"/>
```

Or install via npm.

## Development

After cloning this repo:

```sh
npm install
npm start
```

In another terminal, start the server:

```sh
npm i -g browser-sync
browser-sync start --server --files "docs/index.html, css/tachyons.css"
```

Open your browser to `localhost:3000`.

To only build the css to the `css/` directory, run `npm run build`.
