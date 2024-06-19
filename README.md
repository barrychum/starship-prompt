# Starship Prompt Installation Guide on macOS

## Installation

1. **Install Starship Prompt**:
   ```sh
   brew install starship
   ```

2. **Configure Starship**:
   Add the following line to the end of your `~/.zshrc` (or `~/.bashrc` if using bash):
   ```sh
   eval "$(starship init zsh)"
   ```
   Reload the shell configuration:
   ```sh
   source ~/.zshrc
   ```

3. **Sample Starship config.toml**:
edit ~/.config/starship.toml
use the sample in src diretory

## Fira Nerd Font Installation

**reference**
https://www.nerdfonts.com/cheat-sheet
https://www.nerdfonts.com/font-downloads

1. **Download Fira Code Nerd Font**:
```
brew install --cask font-<FONT NAME>-nerd-font
e.g.
brew install --cask font-fira-code-nerd-font
brew install --cask font-fira-mono-nerd-font
```
2. **Set the Font**:
   - Open **Terminal** Preferences.
   - Navigate to **Profiles** > **Text**.
   - Change the font to **Fira Code Nerd Font**.

## Usage

- Once installed, the Starship prompt will be automatically activated in your terminal.
- Customize Starship by creating a configuration file at `~/.config/starship.toml`.

For further customization options, refer to the [Starship Documentation](https://starship.rs/).

---

This guide provides quick instructions for installing and using the Starship prompt on macOS, along with setting up the Fira Nerd Font.