# Magento PWA Studio Snippets for VS Code
[![Version](https://img.shields.io/visual-studio-marketplace/v/larsroettig.vscode-pwa-studio?style=for-the-badge)](https://img.shields.io/visual-studio-marketplace/d/larsroettig.vscode-pwa-studio?style=for-the-badge)
[![Installs](https://img.shields.io/visual-studio-marketplace/d/larsroettig.vscode-pwa-studio?style=for-the-badge)](https://img.shields.io/visual-studio-marketplace/d/larsroettig.vscode-pwa-studio?style=for-the-badge)


This extension for Visual Studio Code adds snippets for Magento PWA Studio.

![Use Extension](images/use-extension.gif)

See the [CHANGELOG](CHANGELOG.md) for the latest changes


### Visual Studio Marketplace

Launch _Quick Open_:

- [_Linux_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf): `Ctrl+P`
- [_macOS_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf): `⌘P`
- [_Windows_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf): `Ctrl+P`

Paste the following command and press `Enter`:

```shell
ext install larsroettig.vscode-pwa-studio
```

### GitHub Repository Clone

Change to your `.vscode/extensions` [VS Code extensions directory](https://code.visualstudio.com/docs/extensions/install-extension#_side-loading).
Depending on your platform it is located in the following folders:

- _Linux_: `~/.vscode/extensions`
- _macOS_: `~/.vscode/extensions`
- _Windows_: `%USERPROFILE%\.vscode\extensions`


```shell
git clone git@github.com:larsroettig/vscode-pwa-studio.git
```

For development you open the cloned directory and press `F5` then VS-Code open new Window with the loaded extension.

### PWA Studio Snippets

| Snippet                      | Short  Snippet                                           | Purpose |
| :--------------------------- | :------------------------------------------------------------------: | ---------------------------- |
| `pwa-comp`           | `pwac` | Simple function component |
| `pwa-test`              | `pwat` | Snapshot test based on jest |
| `pwa-test-case` | `pwatc`     | Simple Jest Testcase for snapshot |
| `pwa-test-lib`  | `pwatl` | Snapshot test based on react testing library |
| `pwa-export-default` | `pwaed` | Default export for index |
| `pwa-route` | `pwaro` | Venia-UI route target |
| `pwa-route-sub`      | `pwaros` | Venia-UI route child target |
| `pwa-rich-con` | `pwarc` | Venia-UI rich content renderer target |
| `pwa-hook` |     `pwah`     | Peregrine hook target |
| `pwa-hook-sub` | `pwahs` | Peregrine hook target sub |
