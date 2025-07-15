# Empty NPM package to exclude dependencies using `override` in `package.json`

![NPM Last Update](https://img.shields.io/npm/last-update/no-dep)
![NPM Version](https://img.shields.io/npm/v/no-dep)
![NPM Downloads](https://img.shields.io/npm/dm/no-dep)
![npm bundle size](https://img.shields.io/bundlephobia/min/no-dep)
![NPM License](https://img.shields.io/npm/l/no-dep)

## Usage

```json
{
  "override": {
    "some-package-i-dont-need": "npm:no-dep"
  }
}
```

The package consists of a single ESM file:

```javascript
// This file is intentionally left empty
export default {};
```
