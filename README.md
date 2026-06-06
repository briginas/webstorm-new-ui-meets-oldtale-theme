# WebStorm OldTale Dark

WebStorm OldTale Dark is a dark VS Code theme with WebStorm New UI chrome and OldTale-inspired editor colors. It is inspired by the [WebStorm New Dark UI](https://www.jetbrains.com/help/webstorm/new-ui.html) and [Old Tale](https://github.com/topazape/oldtale.nvim) themes.

**Not affiliated with or endorsed by JetBrains.**

If you love the WebStorm feel in VS Code, you might also like [eenaree/webstorm-new-ui-theme](https://github.com/eenaree/webstorm-new-ui-theme). It helped inspire this project.

Substantial portions of the workbench color palette and editor token colors were adapted from upstream MIT-licensed projects. See [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md) for copyright and license notices.

## Preview

![Theme preview](./images/preview-1.png)

### WebStorm OldTale Dark

## Installation

### From VS Code Marketplace

1. Open **Extensions** in VS Code's sidebar. (or from Command Palette (**Ctrl+Shift+P**), run `View: Show Extensions`)
2. Search for `WebStorm OldTale Dark`.
3. Click **Install** to install it.
4. From Command Palette (**Ctrl+Shift+P**), run `Preferences: Color Theme` and pick the theme you want.
   - `WebStorm OldTale Dark`

### From GitHub Releases

1. Download the latest `.vsix` from [GitHub Releases](https://github.com/briginas/webstorm-oldtale-dark-theme/releases).
2. In VS Code, open Command Palette (**Ctrl+Shift+P**) and run `Extensions: Install from VSIX...`.
3. Select the downloaded file.
4. Run `Preferences: Color Theme` and choose `WebStorm OldTale Dark`.

Or from the terminal:

```bash
code --install-extension path/to/webstorm-new-dark-ui-meets-oldtale-1.1.1.vsix
```

## Supported Languages

- TypeScript
- TSX
- HTML
- CSS, SCSS
- Markdown
- JSON

## Recommended Editor Settings

```json
{
  "editor.fontFamily": "Ayuthaya",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,
  "editor.inlayHints.padding": true,
  "editor.bracketPairColorization.enabled": false,
  "color-highlight.markRuler": false
}
```
