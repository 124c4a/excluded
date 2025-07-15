# Empty NPM package to exclude dependencies using `override` in `package.json`

![NPM Last Update](https://img.shields.io/npm/last-update/dont-install)
![NPM Version](https://img.shields.io/npm/v/dont-install)
![NPM Downloads](https://img.shields.io/npm/dm/dont-install)
![npm bundle size](https://img.shields.io/bundlephobia/min/dont-install)
![NPM License](https://img.shields.io/npm/l/dont-install)

## Usage

```json
{
  "override": {
    "some-package-i-dont-need": "npm:dont-install"
  }
}
```

The package consists of a single ESM file:

```javascript
// This file is intentionally left empty
export default {};
```
