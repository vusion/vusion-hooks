# Vusion Hooks

Lint files before committing.

## Usage

``` shell
npm i -D husky vusion-hooks
```

Add following scripts in `package.json`:

``` json
"scripts": {
  "precommit": "node node_modules/vusion-hooks/precommit"
},
```

Make sure eslint or stylelint installed and `.eslintrc` or `.stylelintrc` in current directory.
