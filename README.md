
# Bubble Fork

This is a fork of the 42-header vs code extension. To install it: 

## Build it 

```
 npm install -g @vscode/vsce
```

```
 npm install       # install dependencies
 vsce package --no-yarn     # package the extension as .vsix
```

# Insall it

In VS Code:

- Open Extensions view (Ctrl+Shift+X or Cmd+Shift+X)
- Click the ⋯ (three dots) menu at the top
- Select Install from VSIX…
- Choose your .vsix file


# BR Header for VSCode

This extension provides the 42 header integration in VS Code.

```bash
# ***************************************************************************** #
#                                                     ########  ########        #
#    file.yaml                                        ##     ## ##     ##       #
#                                                     ##     ## ##     ##       #
#    By: ubuntu <ubuntu@bubble-robotics.com>          ########  ########        #
#                                                     ##     ## ##   ##         #
#    Created: 2025/11/12 10:12:28 by ubuntu           ##     ## ##    ##        #
#    Updated: 2025/11/12 10:12:28 by ubuntu           ########  ##     ##       #
#                                                                               #
# ***************************************************************************** #
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.

## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "BRheader.username": string,
  "BRheader.email": string
}
```

## License

MIT
