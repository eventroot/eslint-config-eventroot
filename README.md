# `eslint-config-eventroot`

[![All Contributors](https://img.shields.io/github/all-contributors/eventroot/eslint-config-eventroot?color=ee8449&style=flat-square)](#contributors)

This package contains EventRoot's `eslint` configuration used in our [nodejs][] projects.

## Installation

TBD.

### Configuration in `package.json`

Add a configuration section to the project's `package.json`.

```javascript
"eslintConfig": {
  "extends": [
    "eventroot"
  ],
  "root": true,
  "ignorePatterns": [
    "node_modules/",
    "test/",
    "coverage/"
  ]
}
```

## Contributors ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

[nodejs]: https://nodejs.org/en/
