# Empty NPM package to exclude dependencies using `override` in `package.json`

![NPM Last Update](https://img.shields.io/npm/last-update/excluded)
![NPM Version](https://img.shields.io/npm/v/excluded)
![NPM Downloads](https://img.shields.io/npm/dm/excluded)
![npm bundle size](https://img.shields.io/bundlephobia/min/excluded)
![NPM License](https://img.shields.io/npm/l/excluded)

## Usage

```json
{
    "override": {
        "some-package-i-dont-need": "npm:excluded"
    }
}
```

The package consists of a single ESM file:

```javascript
// This file is intentionally left empty
export default {};
```
