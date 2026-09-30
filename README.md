# Qudian

Qudian is an independent theme project made with love and admiration. It is not affiliated with, endorsed by, or connected to any game or trademark holder.

<img width="1279" height="799" alt="Screenshot 2026-08-25 at 3 33 35 PM" src="https://github.com/user-attachments/assets/3cb1ada0-3982-4dfc-88c1-2ae5d77e2f0e" />


## Contents

- `terminal/` — macOS Terminal profile
- `vscode/` — VS Code / Cursor color theme extension

## Terminal (macOS)

1. Clone or download this repository.
2. Open `terminal/Qudian.terminal`:
   - **Double-click** the file to import it into Terminal, or
   - In Terminal, go to **Settings → Profiles → … → Import…** and select `Qudian.terminal`.
3. Set **Qudian** as your default profile if you want it applied to new windows.

## VS Code / Cursor

### Install from source

1. Clone this repository.
2. In VS Code or Cursor, open the Command Palette and run **Extensions: Install Extension from Location…**
3. Select the `vscode/` folder inside this repo.
4. Open the Command Palette and run **Preferences: Color Theme**, then choose **Qudian**.

### Install from a VSIX (optional)

1. Install the packaging tool:

   ```bash
   npm install -g @vscode/vsce
   ```

2. Build the extension:

   ```bash
   cd vscode
   vsce package
   ```

3. In VS Code or Cursor, run **Extensions: Install from VSIX…** and select the generated `.vsix` file.
4. Select **Qudian** as your color theme.

### Recommended editor settings

Color themes cannot set the typeface. Add these to your user `settings.json` to match the intended look:

```json
"editor.fontFamily": "'Source Code Pro', Menlo, Monaco, 'Courier New', monospace",
"editor.fontSize": 13,
"editor.fontWeight": "400",
"editor.fontLigatures": false,
"editor.fontVariations": true,
"editor.lineHeight": 1.5,
"editor.letterSpacing": 0.3,
"terminal.integrated.fontFamily": "'Source Code Pro', Menlo, Monaco, monospace",
"terminal.integrated.fontSize": 13
```


## License

MIT — see [LICENSE](LICENSE).
