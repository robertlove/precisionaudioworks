# Precision Audioworks

We design, supply, and install quality audio systems for residential and commercial clients.

## Installation

### Clone repository

```shell
git clone git@github.com:robertlove/precisionaudioworks.git
cd precisionaudioworks
```

### Install dependencies

```shell
bundle install
npm i -g purgecss
npm i -g lightningcss-cli
```

## Usage

### Serve site

```shell
bundle exec jekyll serve
```

### Remove unused CSS

```shell
purgecss --config ./purgecss.config.js
```

### Minify CSS

```shell
lightningcss --minify ./_site/assets/css/styles.css -o ./_site/assets/css/styles.css
```

## Contributing

See [Contributing](https://github.com/robertlove/.github/blob/master/CONTRIBUTING.md).

## Credits

See [Contributors](https://github.com/robertlove/precisionaudioworks/graphs/contributors).