# new-mac-setup
Install scripts for setting up a new mac

# Step 1
- install Homebrew
`ruby -e "$(curl -fsSL "https://raw.githubusercontent.com/Homebrew/install/master/install)"`

# Step 2
- install Hombrew Cask
- run `brew tap caskroom/cask`
- then `brew install caskroom/cask/brew-cask`
    - ignore this error
        ```Error: No available Cask for caskroom/cask/brew-cask
        Error: nothing to install```

# Step 3
- run `caskconfig.sh`







brew cask cleanup

# References
- [Homebrew Cask](https://caskroom.github.io/)
- [Homebrew Cask Docs](https://github.com/caskroom/homebrew-cask#learn-more)
- [How to make a cask install script](http://lifehacker.com/how-to-make-your-own-bulk-app-installer-for-os-x-1586252163)



