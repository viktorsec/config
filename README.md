# config

## Apps

- 1Password
- CheatSheet
- Chrome
- CoconutBattery
- DaisyDisk
- Discord
- Dropbox
- Firefox
- Handbrake
- iMovie
- iStat Menus
- Pixelmator
- Slack
- Spectacle
- Spotify
- Steam
- Transmission
- Transmit
- Tunnelblick
- VLC
- Wine and XQuartz
- Xcode

### Chrome Extensions

- [1Password](https://chrome.google.com/webstore/detail/1password-password-manage/aomjjhallfgjeglblehebfpbcfeobpgk)
- [Bumpercar Candysnatch](https://chrome.google.com/webstore/detail/bumpercar-candysnatch/gfgeflpiolnadakikfnhlmlmnbmadbaj)
- Disig Web Signer
- [Full Screen Capture](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)
- [Grammarly](https://chrome.google.com/webstore/detail/grammarly-for-chrome/kbfnbcaeplbcioakkpcpgfkobkghlhen)
- [Hover Zoom](https://chrome.google.com/webstore/detail/hover-zoom/nonjdcjchghhkdoolnlbekcfllmednbl)
- [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp)
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
- [Reddit Enhancement Suite](https://chrome.google.com/webstore/detail/reddit-enhancement-suite/kbmfpngjjgdllneeigpgjifpgocmfgmb)
- [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd)
- [Tamper Chrome](https://chrome.google.com/webstore/detail/tamper-chrome-extension/hifhgpdkfodlpnlmlnmhchnkepplebkb)
- [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)

### VSCode Extensions

- Docker
- ESLint
- markdownlint
- Nasc VSCode Touchbbar
- One Dark Pro
- TSLint

### macOS Dock order:

- Finder
- Launchpad
- Mac App Store
- Chrome
- Firefox
- Safari
- Slack
- Spotify
- Steam
- 1Password
- VSCode
- Xcode
- Hyper
- System Preferences
- Transmit
- Calendar
- TextEdit
- VLC

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

Disable spaces rearranging (Auto Swoosh)

`defaults write com.apple.dock workspaces-auto-swoosh -bool NO`

Show hidden files

1. `defaults write com.apple.finder AppleShowAllFiles YES`
2. `killall Finder`

Install Aerial Apple TV wallpaper

`brew cask install aerial`
