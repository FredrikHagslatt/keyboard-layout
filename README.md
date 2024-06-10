# freppan Custom Keyboard Layout

## Overview

The `freppan` keyboard layout is a customized variant of the US keyboard layout, designed to include additional characters for easier access to specific symbols used in the Swedish languages. This layout also removes the dead key functionality for certain keys to streamline typing.

## Layout Details

### Base Layout
- **Base:** US

### Additions
The following characters are accessible using the `AltGr` key (often the right Alt key):

- `AltGr-2`: å
- `AltGr-3`: ä
- `AltGr-4`: ö
- `AltGr-5`: Å
- `AltGr-6`: Ä
- `AltGr-7`: Ö

### Tweaks
- Removed dead keys functionality on the following keys:
  - `~`
  - `^`
  - `'`
  - `"`

## Installation

To install the `freppan` custom keyboard layout, follow these steps:

### Windows
1. Download the layout installer from the release section.
2. Run the installer and follow the on-screen instructions.
3. After installation, go to **Settings > Time & Language > Language**.
4. Select your language (e.g., English), click **Options**, and add the `freppan` keyboard layout.
5. Remove other layouts if necessary.

### macOS
1. Download the layout file.
2. Copy the layout file to `/Library/Keyboard Layouts` (for all users) or to `~/Library/Keyboard Layouts` (for a single user).
3. Go to **System Preferences > Keyboard > Input Sources**.
4. Click the `+` button and add the `freppan` layout.
5. Remove other layouts if necessary.

### Linux (X11)
1. Download the layout file.
2. Copy the layout file to `/usr/share/X11/xkb/symbols/`.
3. Edit `/usr/share/X11/xkb/rules/evdev.xml` to include the new layout.
4. Use `setxkbmap` to set the layout:
    ```bash
    setxkbmap -layout freppan
    ```
5. Add the layout to your desktop environment settings.

## Usage

Once installed, you can switch to the `freppan` layout using your operating system's keyboard settings. Use the `AltGr` key in combination with the specified number keys to type the additional characters.

## Contributors

- [Your Name](https://github.com/your-github-profile)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
