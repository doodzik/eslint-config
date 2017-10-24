# eslint-config

This repo contains my eslint configuration files

# installation

```
npm install doodzik/eslint-config --save-dev
```

# usage

add the following to the script section of your `package.json`
```
{
  ...
  "scripts": {
    ...
    "lint": "eslint . --fix --ignore-path .gitignore -c ./node_modules/eslint-config/.eslintrc.js ",
    "lint-prod": "eslint . --fix --ignore-path .gitignore -c ./node_modules/eslint-config/.eslintrc.production.js ",
    ...
  }
  ...
}
```
