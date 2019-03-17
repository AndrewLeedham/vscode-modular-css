# vscode-modular-css
[![Visual Studio Marketplace](https://flat.badgen.net/vs-marketplace/v/andrewleedham.vscode-modular-css?color=cyan)](https://marketplace.visualstudio.com/items?itemName=andrewleedham.vscode-modular-css) [![Installs](https://flat.badgen.net/vs-marketplace/i/andrewleedham.vscode-modular-css?color=blue)](https://marketplace.visualstudio.com/items?itemName=andrewleedham.vscode-modular-css) [![Downloads](https://flat.badgen.net/vs-marketplace/d/andrewleedham.vscode-modular-css?color=purple)](https://marketplace.visualstudio.com/items?itemName=andrewleedham.vscode-modular-css) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square)](https://github.com/semantic-release/semantic-release) [![commit style angular](https://flat.badgen.net/badge/commit%20style/angular/red)](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines) [![license MIT](https://flat.badgen.net/badge/license/MIT/orange)](./LICENSE) ![Languages CSS, SCSS, SASS](https://flat.badgen.net/badge/languages/css,scss,sass/yellow?list=1) [![Greenkeeper badge](https://badges.greenkeeper.io/AndrewLeedham/vscode-modular-css.svg?style=flat-square)](https://greenkeeper.io/)

An extension to add [Modular CSS](https://github.com/tivac/modular-css) syntax highlighting to VSCode.

![VSCode Window showing the plugin in action](/highlighting.png)

## Features
Adds the following Modular-CSS specific rule and attribute syntax highlighting on top of regular CSS.
* `@value` variable decleration: regular, namespaced and wildcard imports.
* `composes:` attribute: local and imports.
* `:external` pseudo class: local and imports.
* `:global` pseudo class.

## Known Issues
Currently this extension only supports syntax highlighting. So errors may be thrown if you are using somesort of linter.

---
[CHANGELOG](/CHANGELOG.md) | [LICENSE](/LICENSE)