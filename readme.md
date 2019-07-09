# @titanium/eslint-config


[![@titanium/eslint-config](https://img.shields.io/npm/v/@titanium/eslint-config.png)](https://www.npmjs.com/package/@titanium/eslint-config)

## 📝 Description

ESLint settings package for use with Axway Titanium native mobile apps

> This extends [@geek/eslint-config](https://github.com/brentonhouse/geek-eslint-config) settings for node.js

## 🚀 Getting Started

1. Create new Titanium Alloy project
2. Run `npm init` in project root directory
3. Install `@titanium/eslint-config` in root of project

```
npm install --save-dev @titanium/eslint-config
```

4. Add this as base settings for your project

> If using `.eslintrc.yaml`

```
    extends: '@titanium'
```

> If using `.eslintrc` or  `.eslintrc.json`

```
    "extends": "@titanium",
```