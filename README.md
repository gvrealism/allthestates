# allthestates

A complete list of all license plate states in [Greenville](https://www.roblox.com/games/891852901/).

## Why?

The developers provide no official or complete list of license plate states, making it difficult to implement it programmatically. Example use cases include registration systems.

This works well with [allthecars](https://github.com/gvrealism/allthecars).

## Installation

```bash
npm install --save https://github.com/gvrealism/allthestates
```

This will allow you to import or/and require the package. If you're not using Node.js, you can fetch the list from the [file](https://raw.githubusercontent.com/gvrealism/allthecars/v2/index.js).

## Usage

```js
const states = require('allthestates')
const exists = (name) => states.includes(name)
```

## License

[ISC](https://github.com/gvrealism/allthecars/tree/v2/LICENSE)
