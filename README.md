# config

## macOS

Disable App restrictions autodefaulting to Mac App Store every 30 days

```sudo defaults write /Library/Preferences/com.apple.security GKAutoRearm -bool NO```

Disable spaces rearranging

`defaults write com.apple.dock workspaces-auto-swoosh -bool NO`

Show hidden files

`defaults write com.apple.finder AppleShowAllFiles YES`

`killall Finder`

Install Aerial Apple TV wallpaper

`brew cask install aerial`

### terminal

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
`brew cask install hyper`

### git

`git config --global user.email "hey@viktorsec.com" && git config --global user.name "Viktor Sec"`

don't have to --set-upstream

`git config push.default current`

### atom

`apm install --packages-file package-list.txt`
