# glob-del
> Del based on globby.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```shell
npm install -S @feizheng/glob-del
```

## usage
```js
import del from '@feizheng/glob-del';

del(['**', '!.git']);
// https://github.com/sindresorhus/del
```

## license
Code released under [the MIT license](./LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@feizheng/glob-del
[version-url]: https://npmjs.org/package/@feizheng/glob-del

[license-image]: https://img.shields.io/npm/l/@feizheng/glob-del
[license-url]: https://github.com/afeiship/glob-del/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@feizheng/glob-del
[size-url]: https://github.com/afeiship/glob-del/blob/master/dist/glob-del.min.js

[download-image]: https://img.shields.io/npm/dm/@feizheng/glob-del
[download-url]: https://www.npmjs.com/package/@feizheng/glob-del
