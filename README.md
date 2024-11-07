My Complete Shell Setup
--------

Install https://ohmyz.sh/#install
```
brew install fish
brew install starship
```
Add the following to the end of `~/.zshrc`:
```
eval "$(starship init zsh)"
```

# Themes Setup

### Terminal Emulator: iTerm2
- Theme: Minimal
Change: iTerm2 > Settings > Appearance > General > Theme > Minimal

- Color Scheme: [Snazzy, download, open](https://github.com/sindresorhus/iterm2-snazzy)
Change: iTerm2 > Settings > Profiles > Color

- Font: [FiraCode Nerd Font](https://www.nerdfonts.com/font-downloads)
Change: iTerm2 > Settings > Profiles > Text
  
- Shell: Fish Shell
- Configuration: [alias.fish](alias.fish) and [config.fish](config.fish) files
- Prompt: Starship

```
brew install lsd
brew install fzf
brew install tide
brew install neovim
```


