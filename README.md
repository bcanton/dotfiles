# Barry’s dotfiles

I forked Mathias's dotfiles repo and then replaced most of his dotfiles with mine.

## Installation

### Using Git and the bootstrap script

The bootstrapper script will pull in the latest version and copy the files to your home folder.

```bash
git clone https://github.com/bcanton/dotfiles.git && cd dotfiles && source bootstrap.sh
```

To update, `cd` into your local `dotfiles` repository and then:

```bash
source bootstrap.sh
```

Alternatively, to update while avoiding the confirmation prompt:

```bash
set -- -f; source bootstrap.sh
```

# Terminal Customization

* Install [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh)
* Install Solarized for Terminal - https://github.com/tomislav/osx-terminal.app-colors-solarized
* Font: [Inconsolata](https://github.com/powerline/fonts)
* Might need to rerun bootstrap.sh after this since .zshrc might be overwritten.

# MacVim
* [MacVim](https://stackoverflow.com/questions/21012203/how-can-i-install-macvim-on-os-x)
* To make MacVim findable by Spotlight, right click the homebrew MacVim application (in /usr/local/Cellar/macvim/) > "Make Alias" and moving that into /Applications.
* [Janus](https://github.com/carlhuda/janus)

# Google Calendar
* [Nativefier](https://www.npmjs.com/package/nativefier)

# Set search domains so you can just type hostnames in terminal
Go to network preferences, DNS, add openvpn explicitly and in the second position add ginkgobioworks.com

# Generate public/private keys
ssh-keygen

# Enable all possible time machine backups
defaults write com.apple.systempreferences TMShowUnsupportedNetworkVolumes 1

When setting up a new Mac, you may want to install some common [Homebrew](http://brew.sh/) formulae (after installing Homebrew, of course):

```bash
brew bundle ~/Brewfile
```

### Install native apps with `brew cask`

You could also install native apps with [`brew cask`](https://github.com/phinze/homebrew-cask):

```bash
brew bundle ~/Caskfile
```

## Thanks to…

* [Mathias Bynens](http://mathiasbynens.be/)
* @ptb and [his _OS X Lion Setup_ repository](https://github.com/ptb/Mac-OS-X-Lion-Setup)
* [Ben Alman](http://benalman.com/) and his [dotfiles repository](https://github.com/cowboy/dotfiles)
* [Chris Gerke](http://www.randomsquared.com/) and his [tutorial on creating an OS X SOE master image](http://chris-gerke.blogspot.com/2012/04/mac-osx-soe-master-image-day-7.html) + [_Insta_ repository](https://github.com/cgerke/Insta)
* [Cãtãlin Mariş](https://github.com/alrra) and his [dotfiles repository](https://github.com/alrra/dotfiles)
* [Gianni Chiappetta](http://gf3.ca/) for sharing his [amazing collection of dotfiles](https://github.com/gf3/dotfiles)
* [Jan Moesen](http://jan.moesen.nu/) and his [ancient `.bash_profile`](https://gist.github.com/1156154) + [shiny _tilde_ repository](https://github.com/janmoesen/tilde)
* [Lauri ‘Lri’ Ranta](http://lri.me/) for sharing [loads of hidden preferences](http://osxnotes.net/defaults.html)
* [Matijs Brinkhuis](http://hotfusion.nl/) and his [dotfiles repository](https://github.com/matijs/dotfiles)
* [Nicolas Gallagher](http://nicolasgallagher.com/) and his [dotfiles repository](https://github.com/necolas/dotfiles)
* [Sindre Sorhus](http://sindresorhus.com/)
* [Tom Ryder](http://blog.sanctum.geek.nz/) and his [dotfiles repository](https://github.com/tejr/dotfiles)
* [Kevin Suttle](http://kevinsuttle.com/) and his [dotfiles repository](https://github.com/kevinSuttle/dotfiles) and [OSXDefaults project](https://github.com/kevinSuttle/OSXDefaults), which aims to provide better documentation for [`~/.osx`](http://mths.be/osx)
* [Haralan Dobrev](http://hkdobrev.com/)
