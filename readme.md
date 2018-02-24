# Nate's Dotfiles

So far mostly a modded fork of https://medium.com/@driesvints/getting-started-with-dotfiles-76bf046d035c

```zsh
brew install mackup
mackup backup
```

### Setting up your Mac

1. Update macOS to the latest version with the App Store
3. Install macOS Command Line Tools by running `xcode-select --install`
4. Copy public and private SSH keys to `~/.ssh` and make sure they're set to `600`
5. Clone this repo to `~/.dotfiles`
6. Append `/usr/local/bin/zsh` to the end of your `/etc/shells` file
7. Run `install.sh` to start the installation
8. Restore preferences by running `mackup restore`
9. Restart your computer to finalize the process

Add the contents below to a `.zshrc` file in your user directory.

```zsh
# Load Zsh
source ~/.dotfiles/.zshrc
```
