# Lazygit Configuration

Personal configuration files for [Lazygit](https://github.com/jesseduffield/lazygit), a simple terminal UI for git commands.

## Overview

This repository contains my custom Lazygit configuration to enhance the git workflow experience in the terminal.

## Configuration

### Keybindings (`config.yml`)

Custom keybindings for improved navigation:

- **Tab Navigation**: Use `<tab>` to move to the next tab and `<backtab>` (Shift+Tab) to move to the previous tab
- **Block Navigation**: Alternative block navigation shortcuts are disabled for a cleaner keybinding setup

## Installation

To use this configuration:

1. Clone this repository to your Lazygit config directory:
   ```bash
   git clone https://github.com/lucaslenglet/Lazygit.Config.git ~/.config/lazygit
   ```
   
   On Windows, the default location is:
   ```bash
   %LOCALAPPDATA%\lazygit
   ```

2. Or manually copy `config.yml` to your Lazygit configuration directory

## Repository Structure

```
.
├── config.yml    # Main configuration file with keybindings
├── .gitignore    # Git ignore rules (excludes state.yml)
└── README.md     # This file
```

## Notes

- `state.yml` is excluded from version control as it contains local state information
- Only the `config.yml` file is tracked to maintain a clean, portable configuration

## Resources

- [Lazygit Documentation](https://github.com/jesseduffield/lazygit/tree/master/docs)
- [Lazygit Keybindings Guide](https://github.com/jesseduffield/lazygit/blob/master/docs/keybindings/Keybindings_en.md)
- [Lazygit Config Options](https://github.com/jesseduffield/lazygit/blob/master/docs/Config.md)

## License

This is a personal configuration repository. Feel free to use and modify as needed.
