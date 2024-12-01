# min-rect

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![bundle][bundle-src]][bundle-href]
[![JSDocs][jsdocs-src]][jsdocs-href]
[![License][license-src]][license-href]

## Description

compute the minimum bounding box (2D)

## How to use

```ts
import { MBR, Vector2 } from 'min-rect'

const points = [
  [0, 0],
  [1, 0],
  [0, 1],
  [1, 1],
].map(([x, y]) => new Vector2(x, y))

const mbr = mbr.fromPoints(points)

console.log(mbr)
/**
 * {
 *   halfSize: Vector2 { x: 0.5, y: 0.5 },
 *   center: Vector2 { x: 0.5, y: 0.5 },
 *   rotation: 0
 * }
 */
```

<!-- ## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/bjorn/static/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/bjorn/static/sponsors.svg'/>
  </a>
</p> -->

## License

[MIT](./LICENSE) License © 2024-PRESENT [Bjorn](https://github.com/bjorn)

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/min-rect?style=flat&colorA=080f12&colorB=1fa669
[npm-version-href]: https://npmjs.com/package/min-rect
[npm-downloads-src]: https://img.shields.io/npm/dm/min-rect?style=flat&colorA=080f12&colorB=1fa669
[npm-downloads-href]: https://npmjs.com/package/min-rect
[bundle-src]: https://img.shields.io/bundlephobia/minzip/min-rect?style=flat&colorA=080f12&colorB=1fa669&label=minzip
[bundle-href]: https://bundlephobia.com/result?p=min-rect
[license-src]: https://img.shields.io/github/license/bjorn/min-rect.svg?style=flat&colorA=080f12&colorB=1fa669
[license-href]: https://github.com/bjorn/min-rect/blob/main/LICENSE
[jsdocs-src]: https://img.shields.io/badge/jsdocs-reference-080f12?style=flat&colorA=080f12&colorB=1fa669
[jsdocs-href]: https://www.jsdocs.io/package/min-rect
