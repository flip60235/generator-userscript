# @violentmonkey/generator-userscript

![NPM](https://img.shields.io/npm/v/@violentmonkey/generator-userscript.svg)

Yeoman generator to create a workspace for userscript easily.

Node.js v10.0+ is required.

## Features

- Modern syntax
  - JavaScript ESNext or TypeScript
  - JSX for DOM powered by [@violentmonkey/dom](https://github.com/violentmonkey/vm-dom)
- CSS
  - CSSNext powered by [PreCSS](https://github.com/jonathantneal/precss)
  - CSS modules (only applied for `.module.css` files)

Read [this](https://violentmonkey.github.io/guide/using-modern-syntax/) for more details.

## Usage

```sh
$ mkdir my-script
$ cd my-script

# Use the latest version from git
$ npx -p https://github.com/violentmonkey/generator-userscript.git -p yo yo @violentmonkey/userscript
```
