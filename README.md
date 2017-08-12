# codename-greek

> Greek letter names parser for [Codename](https://github.com/khaosdoctor/Codename) (Standalone)

## Usage

Install the package using either `npm install codename-greek --save` or `yarn add codename-greek`.

Require it and use the function `parse`:

```js
const greek = require('codename-greek')

console.log(greek.parse('2.1.4').codenameText) // V2.1.4 - Beta
```

For more information about the API, see [Codename](https://github.com/khaosdoctor/Codename) project, this parser only abstracts the `parse` function, returning an instance of the original Codename parser