# baggo

> baggo bags, does not unbag

## Installation

```sh
$ npm install --save baggo
```

## Usage

### `createBaggo()`

create baggo

```js
var baggo = createBaggo()
```

### `baggo(item)`

put in baggo

**warning:** does not unbaggo

```js
baggo('$$$')
```

### `baggo.look(i)`

look in baggo

```js
baggo('(❍ᴥ❍ʋ)')

baggo.look(0) === '(❍ᴥ❍ʋ)'
```

## License

MIT © [Jamen Marz](https://git.io/jamen)

---

[![version](https://img.shields.io/npm/v/baggo.svg?style=flat-square)][package] [![travis](https://img.shields.io/travis/baggo/baggo.svg?style=flat-square)](https://travis-ci.org/jamen/baggo) [![downloads](https://img.shields.io/npm/dt/baggo.svg?style=flat-square)][package] [![license](https://img.shields.io/npm/l/express.svg?style=flat-square)][package] [![follow](https://img.shields.io/github/followers/baggo.svg?style=social&label=Follow)](https://github.com/baggo)

[package]: https://npmjs.org/package/baggo
