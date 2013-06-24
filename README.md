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

### Xcode
- Downloads > Command Line Tools

### Safari Extensions
- [Live Reload](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-)
- [Pocket](http://getpocket.com/safari/)

===
After Dropbox
### Dropbox Apps
- Font Explorer Setup (Sync)
- Cyberduck (Sync)
- 1Password Setup

===
After Xcode (sequentially)
- [Homebrew](http://mxcl.github.io/homebrew/)
- Github ```brew install git```
- [Setup Git](https://help.github.com/articles/set-up-git)
- Ruby ```brew install ruby```
- Rails ```gem install rails```
- Postgis ```brew install postgis```
- Postgres ```brew install postgres```
- Imagemagik ```brew install imagemagick```

===
After Github
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
