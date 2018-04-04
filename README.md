# tslint-config-leapfrog

[![npm version](https://badge.fury.io/js/tslint-config-leapfrog.svg)](https://badge.fury.io/js/tslint-config-leapfrog)
[![downloads](http://img.shields.io/npm/dt/tslint-config-leapfrog.svg)](https://npmjs.org/package/tslint-config-leapfrog)

Set of [TSLint](https://palantir.github.io/tslint/) rules for TypeScript projects at Leapfrog.

**`tslint-config-leapfrog` adds rules from `tslint-consistent-codestyle` and `tslint-react`.**

## Requires

* TypeScript **>= 2.5.0**
* TSLint     **>= 5.8.0**

## Usage

Add `tslint-config-leapfrog` as a dev dependency.

```bash
yarn add tslint-config-leapfrog --dev
```

Include `tslint-config-leapfrog` in your [tslint.json](https://palantir.github.io/tslint/usage/configuration/) file.

```json
{
  "extends": [
    "tslint-config-leapfrog"
  ]
}
```

For projects using React, include `tslint-config-leapfrog/react` which contains TSLint rules specific to React.

```json
{
  "extends": [
    "tslint-config-leapfrog/react"
  ]
}
```

## License

[MIT](LICENSE)
