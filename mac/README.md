**Disable the sound effects on boot**
```
sudo nvram SystemAudioVolume=" "
```

**Disable shadow in screenshots**
```
defaults write com.apple.screencapture disable-shadow -bool true
```

**Set a blazingly fast keyboard repeat rate**
```
defaults write NSGlobalDomain KeyRepeat -int 1
defaults write NSGlobalDomain InitialKeyRepeat -int 10
```

**Add iOS & Watch Simulator to Launchpad**
```
sudo ln -sf "/Applications/Xcode.app/Contents/Developer/Applications/Simulator.app" "/Applications/Simulator.app"
sudo ln -sf "/Applications/Xcode.app/Contents/Developer/Applications/Simulator (Watch).app" "/Applications/Simulator (Watch).app"
```

**Privacy: don’t send search queries to Apple**
```
defaults write com.apple.Safari UniversalSearchEnabled -bool false
defaults write com.apple.Safari SuppressSearchSuggestions -bool true
```