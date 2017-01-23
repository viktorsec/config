# config

## macOS

Disable App restrictions autodefaulting to Mac App Store every 30 days

```sudo defaults write /Library/Preferences/com.apple.security GKAutoRearm -bool NO```

Show hidden files

`defaults write com.apple.finder AppleShowAllFiles YES`
`killall Finder`
