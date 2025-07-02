# fivem-fxmanifest-snippets
VSCode Extension for FiveM FXManifest Snippets

## Features

- Provides handy code snippets for creating `fxmanifest.lua` files in FiveM scripts.
- Includes snippets for both script manifests (`fxmanifest:script`) and MLO manifests (`fxmanifest:mlo`).
- Speeds up development by auto-completing common manifest templates.
- Easy to trigger: just type the prefix (`fxmanifest:script` or `fxmanifest:mlo`) and press TAB.
- Helps avoid syntax errors by providing well-structured manifest boilerplate.

## Requirements

- Visual Studio Code
- Works best with Lua language support extension installed (recommended: [sumneko.lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua))
- Basic knowledge of FiveM resource manifest files (`fxmanifest.lua`).

## Extension Settings

This extension does not currently contribute any VS Code settings.

## Known Issues

- Snippets are designed for standard `fxmanifest.lua` structure; highly customized manifests may require manual edits.
- Currently supports only the two snippet types (`fxmanifest:script` and `fxmanifest:mlo`).
- No dynamic snippet generation yet (all snippets are static templates).

## Release Notes

### 1.0.0

- Initial release with two snippet templates for FiveM manifests:
  - `fxmanifest:script`: Server/client/shared script manifest
  - `fxmanifest:mlo`: Map loader object manifest

**Enjoy!**
