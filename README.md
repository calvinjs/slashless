# Slashless

Middleware for Dylan which redirects trailing slash requests.

## Install

`npm install @dylan/slashless`

## Usage

``` js
const slashless = require('@dylan/slashless');
app.use(slashless());
```

`/foo/` redirects to `/foo`.
