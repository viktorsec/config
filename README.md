# config

## Apps

#### 1Password
#### Atom

1. `cp Atom/config.cson ~/.atom/config.cson`
2. `apm install --packages-file Atom/package-list.txt`

#### Chrome

Install Extensions

- [1Password](https://chrome.google.com/webstore/detail/1password-password-manage/aomjjhallfgjeglblehebfpbcfeobpgk)
- [Bumpercar Candysnatch](https://chrome.google.com/webstore/detail/bumpercar-candysnatch/gfgeflpiolnadakikfnhlmlmnbmadbaj)
- [Goo.gl Shortener](https://chrome.google.com/webstore/detail/url-shortener-lite-with-g/mnnkfmkiefebamlmijhohmjaajilnlen)
- [Hover Zoom](https://chrome.google.com/webstore/detail/hover-zoom/nonjdcjchghhkdoolnlbekcfllmednbl)
- [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp)
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
- [Reddit Enhancement Suite](https://chrome.google.com/webstore/detail/reddit-enhancement-suite/kbmfpngjjgdllneeigpgjifpgocmfgmb)
- [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd)
- [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)

#### DaisyDisk
#### Dropbox
#### iStat Menus
#### Pixelmator
#### Slack
#### Spotify
#### Steam
#### Transmission
#### Transmitj
#### Wine and XQuartz
#### Xcode

## macOS

### Homebrew

1. `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. `brew update`

### terminal

#### Oh My Zsh

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

#### Hyper.js

1. `brew cask install hyper`
2. `cp .hyper.js ~/.hyper.js`

### Git

1. `brew install git`
2. `git config --global user.email "hey@viktorsec.com" && git config --global user.name "Viktor Sec"`
3. `git config --global push.default current` so I don't have to --set-upstream

### Node & friends

1. `brew install node`
2. `brew install yarn`
3. `npm install -g grunt-cli`

### macOS tweaks

Disable App restrictions autodefaulting to Mac App Store every 30 days

1. `sudo spctl --master-disable` (since macOS Sierra)
2. `sudo defaults write /Library/Preferences/com.apple.security GKAutoRearm -bool NO`

Disable spaces rearranging

`defaults write com.apple.dock workspaces-auto-swoosh -bool NO`

Show hidden files

1. `defaults write com.apple.finder AppleShowAllFiles YES`
2. `killall Finder`

Install Aerial Apple TV wallpaper

`brew cask install aerial`
