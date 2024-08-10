# Helix Editor Amberwood Theme for VS Code

![Theme Preview](images/Screenshot%202024-08-10%20at%2010.50.44 PM.png)

## Description

The Helix Editor Amberwood Theme is a visually harmonious and carefully crafted color scheme for Visual Studio Code. Inspired by the Helix editor's aesthetics, this theme offers a seamless and pleasing visual experience across all areas of your VS Code interface.

### Key Features

- **Cohesive Design**: Carefully balanced colors that blend editor, sidebar, and other UI elements.
- **Enhanced Readability**: Optimized contrast for comfortable long coding sessions.
- **Syntax Highlighting**: Thoughtfully chosen colors for clear and intuitive code representation.
- **Accent Colors**: Strategic use of accent colors to highlight important elements without overwhelming the senses.

## Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Helix Amberwood Theme`
3. Click **Install** to install it.
4. Click **Reload** to reload the editor.
5. Code > Preferences > Color Theme > **Helix Amberwood Theme**

## Manual Installation

1. Download the `Helix Amberwood-color-theme.json` file.
2. Go to your VS Code extensions folder:
   - Windows: `%USERPROFILE%\.vscode\extensions\`
   - macOS/Linux: `~/.vscode/extensions/`
3. Create a new folder named `Helix-Amberwood`.
4. Place the downloaded JSON file inside this new folder.
5. Restart VS Code.
6. Select the theme: Code > Preferences > Color Theme > **Helix Amberwood**

## Customization

If you want to customize the theme further:

1. Go to `File > Preferences > Settings`
2. Search for `workbench.colorCustomizations`
3. Add your overrides inside the curly braces

Example:

```json
"workbench.colorCustomizations": {
    "[Helix Amberwood]": {
        "editor.background": "#0E0F13"
    }
}
```

## Contributing

Contributions are welcome, just open a PR.

## Changelog

For a detailed list of changes and version history, please see the [CHANGELOG.md](CHANGELOG.md) file.

## License

This theme is released under the [MIT License](LICENSE).

## Acknowledgements

- Inspired by the Helix editor's color scheme originally by [Gagan Janjua](https://github.com/gj1118?tab=repositories)
- Thanks to all contributors and users for their valuable feedback

---

Enjoy coding with your new Helix Editor Amberwood Theme! If you have any issues or suggestions, please open an issue on our GitHub repository.