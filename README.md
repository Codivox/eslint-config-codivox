# eslint-config-codivox

ESlint rules configuration for consistent linting rules across Codivox projects

## Usage

 - Install `eslint-config-codivox` module.

```
npm install --save-dev eslint-config-codivox
```

 - Create a new `.eslintrc.js` file on the root of your project and extend a configuration.

```
module.exports = {
  extends: "codivox"
};
```

 - Add a new script to your package.json in order to run eslint.

```
{
  "scripts": {
    "lint": "eslint . --ext .ts,.tsx,.js,.jsx"
  }
}
```
