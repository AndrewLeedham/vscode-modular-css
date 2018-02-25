# vscode-modular-css

An extension to add Modular-CSS syntax highlighting to VSCode.

## Features

Adds the following Modular-CSS specific rule and attribute syntax highlighting on top of regular CSS.
* `@value` variable decleration: regular, namespaced and wildcard imports.
* `composes:` attribute: local and imports.
* `:external` pseudo class: local and imports.
* `:global` pseudo class.

## Known Issues

Currently this extension only supports syntax highlighting. So errors may be thrown if you are using somesort of linter.

## Release Notes
See CHANGELOG.md for details.

### 1.2.2
* Changed `package.json` repository field to fix icon error. And cleaned up naming.