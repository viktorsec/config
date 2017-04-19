# config

## macOS

Disable App restrictions autodefaulting to Mac App Store every 30 days

```sudo defaults write /Library/Preferences/com.apple.security GKAutoRearm -bool NO```

Show hidden files

`defaults write com.apple.finder AppleShowAllFiles YES`

`killall Finder`

Install Aerial Apple TV wallpaper

`brew cask install aerial`

### terminal

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
`brew cask install hyper`

### git

don't have to --set-upstream

`git config push.default current`

### atom

`apm install nuclide`

packages

- atom-react-native-autocomplete
- code-stats-atom
- figlet
- linter-eslint
- markdown-preview-plus
- merge-conflicts
- minimap
- minimap-pigments
- redux-devtools
- trailing-spaces
- activate-power-mode
