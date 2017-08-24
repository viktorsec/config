# config

## Apps

- 1Password
- Atom
- Chrome
- Dropbox
- Slack
- Spotify
- Steam
- Transmission
- Wine and XQuartz

## macOS

### Homebrew

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### terminal

#### Oh My Zsh

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

#### Hyper.js

1. `brew cask install hyper`
2. `cp .hyper.js ~/.hyper.js`

### git

1. `brew install git`
2. `git config --global user.email "hey@viktorsec.com" && git config --global user.name "Viktor Sec"`
3. `git config --global push.default current` so I don't have to --set-upstream

### atom

`apm install --packages-file package-list.txt`

### macOS tweaks

Disable App restrictions autodefaulting to Mac App Store every 30 days

```sudo defaults write /Library/Preferences/com.apple.security GKAutoRearm -bool NO```

Disable spaces rearranging

`defaults write com.apple.dock workspaces-auto-swoosh -bool NO`

Show hidden files

`defaults write com.apple.finder AppleShowAllFiles YES`

`killall Finder`

Install Aerial Apple TV wallpaper

`brew cask install aerial`
