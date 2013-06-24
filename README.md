genesis
=======

## Reinstall checklist
In sequential order with breaks for dependencies

### App Store
- Cloud
- Color Snapper
- Sparrow
- LiveReload
- Xcode
- MockSMTP
- Pages
- Numbers
- Keynote

### Downloads
- [Dropbox](http://dropbox.com)
- [Alfred](http://www.alfredapp.com)
- [Adobe Suite](https://licensing.adobe.com/sap/bc/bsp/sap/zliclogin/login.htm)
- [1Password](https://agilebits.com/downloads/1Password/Mac)
- [Spectacle](http://spectacleapp.com)
- [Cyberduck](http://cyberduck.ch)
- [Chrome](http://www.google.com/mac/)
- [Hipchat](https://www.hipchat.com/mac)
- [Instashare](http://instashareapp.com)
- [Skype](http://www.skype.com/en/download-skype/skype-for-computer/)
- [Spotify](https://www.spotify.com/us/download/mac/)
- [QuickRes](http://www.quickresapp.com)
- [TextMate](http://macromates.com/download)
- [XtraFinder](http://www.trankynam.com/xtrafinder/)

### Xcode
- Downloads > Command Line Tools

### Safari Extensions
- [Live Reload](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-)
- [Pocket](http://getpocket.com/safari/)

===
### After Xcode (sequentially)
- [Homebrew](http://mxcl.github.io/homebrew/)
- Github ```brew install git```
- [Setup Git](https://help.github.com/articles/set-up-git)
- Hub ```brew install hub```
- Ruby ```brew install ruby```
- Rails ```gem install rails```
- Postgis ```brew install postgis```
- Postgres ```brew install postgres```
- Imagemagik ```brew install imagemagick```

===
### Repos
- [Spire](https://github.com/42floors/spire)
- [MLS](https://github.com/42floors/mls)
- [TM Bundles](https://github.com/malomalo/tmbundles)

### Profile
```
alias spire="cd ~/code/spire"
alias profile="mate ~/.profile"
alias mls="cd ~/code/mls"
alias bundles="cd ~/Library/Application\ Support/TextMate/Bundles/"
eval "$(hub alias -s)"
export PATH="/usr/local/bin:/usr/local/opt/ruby/bin:/Developer/usr/bin:/usr/local/sbin:/usr/local/mysql/bin:~/bin:$PATH"
### Added by the Heroku Toolbelt
export PATH="/usr/local/heroku/bin:$PATH"
```

### Git Config
```
[user]
  name = Ben Ehmke
	email = benehmke@gmail.com
[credential]
	helper = osxkeychain
[color]
	ui = true
	diff = auto
	status = auto
	branch = auto
	interactive = auto
[diff]
	tool = opendiff
[merge]
	tool = opendiff
	summary = true
[core]
	editor = mate -w
	excludesfile = ~/.gitignore
[push]
	default = simple
[alias]
	st = status
	com = commit
	br = branch
	co = checkout
	unstage = reset HEAD
    cp = cherry-pick
```
---
### After Dropbox
- Font Explorer Setup (Sync)
- Cyberduck (Sync)
- 1Password Setup
