# @womorg/repudiandae-dolorum-unde [![Build](https://circleci.com/gh/pagekit/@womorg/repudiandae-dolorum-unde.svg?style=shield)](https://circleci.com/gh/pagekit/@womorg/repudiandae-dolorum-unde) [![Downloads](https://img.shields.io/npm/dm/@womorg/repudiandae-dolorum-unde.svg)](https://www.npmjs.com/package/@womorg/repudiandae-dolorum-unde) [![jsdelivr](https://data.jsdelivr.com/v1/package/npm/@womorg/repudiandae-dolorum-unde/badge?style=rounded)](https://www.jsdelivr.com/package/npm/@womorg/repudiandae-dolorum-unde) [![Version](https://img.shields.io/npm/v/@womorg/repudiandae-dolorum-unde.svg)](https://www.npmjs.com/package/@womorg/repudiandae-dolorum-unde) [![License](https://img.shields.io/npm/l/@womorg/repudiandae-dolorum-unde.svg)](https://www.npmjs.com/package/@womorg/repudiandae-dolorum-unde)

The plugin for [Vue.js](http://vuejs.org) provides services for making web requests and handle responses using a [XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest) or JSONP.

## Features

- Supports the [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise) API and [URI Templates](https://medialize.github.io/URI.js/uri-template.html)
- Supports [interceptors](docs/http.md#interceptors) for request and response
- Supports latest Firefox, Chrome, Safari, Opera and IE9+
- Supports Vue 1.0 & Vue 2.0
- Compact size 14KB (5.3KB gzipped)

## Installation
You can install it via [yarn](https://yarnpkg.com/) or [NPM](http://npmjs.org/).
```
$ yarn add @womorg/repudiandae-dolorum-unde
$ npm install @womorg/repudiandae-dolorum-unde
```

### CDN
Available on [jsdelivr](https://cdn.jsdelivr.net/npm/@womorg/repudiandae-dolorum-unde@1.5.3), [unpkg](https://unpkg.com/@womorg/repudiandae-dolorum-unde@1.5.3) or [cdnjs](https://cdnjs.com/libraries/@womorg/repudiandae-dolorum-unde).
```html
<script src="https://cdn.jsdelivr.net/npm/@womorg/repudiandae-dolorum-unde@1.5.3"></script>
```

## Example
```js
{
  // GET /someUrl
  this.$http.get('/someUrl').then(response => {

    // get body data
    this.someData = response.body;

  }, response => {
    // error callback
  });
}
```

## Documentation

- [Configuration](docs/config.md)
- [HTTP Requests/Response](docs/http.md)
- [Creating Resources](docs/resource.md)
- [Code Recipes](docs/recipes.md)
- [API Reference](docs/api.md)

## Changelog

Details changes for each release are documented in the [release notes](https://github.com/womorg/repudiandae-dolorum-unde/releases).

## Contribution

If you find a bug or want to contribute to the code or documentation, you can help by submitting an [issue](https://github.com/womorg/repudiandae-dolorum-unde/issues) or a [pull request](https://github.com/womorg/repudiandae-dolorum-unde/pulls).

## License

[MIT](http://opensource.org/licenses/MIT)
