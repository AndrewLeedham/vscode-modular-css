# vscode-modular-css

> An extension to add [Modular CSS](https://github.com/tivac/modular-css) syntax highlighting to VSCode.

[![Travis CI Status][actions-badge]][actions-link]
[![Visual Studio Marketplace][vscode-badge]][vscode-link]
[![Installs][installs-badge]][installs-link]
[![Downloads][downloads-badge]][downloads-link]
[![semantic-release][semantic-release-badge]][semantic-release-link]
[![commit style angular][commit-style-badge]][commit-style-link]
[![license MIT][license-badge]][license-link]
![Languages CSS, SCSS, SASS][languages-badge]
[![Dependabot Status][dependabot-badge]][dependabot-link]


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

[actions-badge]: https://flat.badgen.net/github/status/AndrewLeedham/vscode-modular-css/master/Github%20Actions
[actions-link]: https://github.com/AndrewLeedham/vscode-modular-css/actions
[vscode-badge]: https://flat.badgen.net/vs-marketplace/v/andrewleedham.vscode-modular-css?color=cyan
[vscode-link]: https://marketplace.visualstudio.com/items?itemName=andrewleedham.vscode-modular-css
[installs-badge]: https://flat.badgen.net/vs-marketplace/i/andrewleedham.vscode-modular-css?color=blue
[installs-link]: https://marketplace.visualstudio.com/items?itemName=andrewleedham.vscode-modular-css
[downloads-badge]: https://flat.badgen.net/vs-marketplace/d/andrewleedham.vscode-modular-css?color=purple
[downloads-link]: https://marketplace.visualstudio.com/items?itemName=andrewleedham.vscode-modular-css
[semantic-release-badge]: https://flat.badgen.net/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80/semantic%20release/e10079
[semantic-release-link]: https://github.com/semantic-release/semantic-release
[commit-style-badge]: https://flat.badgen.net/badge/commit%20style/angular/red
[commit-style-link]: https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines
[license-badge]: https://flat.badgen.net/badge/license/MIT/orange
[license-link]: ./LICENSE
[languages-badge]: https://flat.badgen.net/badge/languages/css,scss,sass/yellow?list=1
[dependabot-badge]: https://flat.badgen.net/dependabot/AndrewLeedham/vscode-modular-css?icon=dependabot
[dependabot-link]: https://dependabot.com
