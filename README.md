# Vanilla Brochure Theme

This is the Vanilla Framework theme for brochure based websites.

## Getting started

```bash
npm i
gulp build
```
## Vanilla brochure theme local development

To develop on Vanilla itself, simply pull down the project and make changes.

To test it locally using our recommended tooling, you need to first install dependencies:

You need to have bundler installed

``` bash
gem install bundler
```

You need to have node and npm. To install follow the [installation instructions](https://docs.npmjs.com/getting-started/installing-node) on this page.

``` bash
bundle install
npm install
```

You can then compile your Sass changes into `build/css/build.css` by running:

``` bash
gulp build
```

Or you can run a local server to view your changes live with:

``` bash
gulp jekyll
```
