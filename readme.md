# eslint-config-depersgroep

De Persgroep ESLint [Shareable Config](https://eslint.org/docs/developer-guide/shareable-configs) (`.eslintrc`).

## Usage

Install from npm public registry

```
npm install eslint-config-persgroep --save-dev
```

Add the `extends` array to your `.eslintrc` with the config sets you need.

```
extends:
  - persgroep
  - persgroep/node  # if using node
  - persgroep/es6   # if using ES6
```

## Troubleshooting

- If your Editor/IDE/Shell is using global eslint you should also install this package global (-g).
