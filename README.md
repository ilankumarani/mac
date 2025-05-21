# mac


### SHOW HIDDEN FILES:
```shell
defaults write com.apple.Finder AppleShowAllFiles true
```

### HIDE HIDDEN FILES:
```shell
defaults write com.apple.Finder AppleShowAllFiles false
```

### KILL FINDER:
```shell
killall Finder
```

### set path in mac using **.zshrc** file
* **.zshrc** file location in mac **~/Users/ilankumaran/.zshrc**
```shell
open ~/.zshrc
```
* setting path in **.zshrc** file
```text
export PATH="$(brew --prefix python)/libexec/bin:$PATH"
```