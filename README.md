# Empty NPM package to exclude dependencies using `override` in `package.json`

![NPM Last Update](https://img.shields.io/npm/last-update/just-no)
![NPM Version](https://img.shields.io/npm/v/just-dep)
![NPM Downloads](https://img.shields.io/npm/dm/just-dep)
![npm bundle size](https://img.shields.io/bundlephobia/min/just-dep)
![NPM License](https://img.shields.io/npm/l/just-dep)

## Usage

```json
{
  "override": {
    "some-package-i-dont-need": "npm:just-no"
  }
}
```

The package consists of a single ESM file:

```javascript
// This file is intentionally left empty
export default {};
```
