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
- Quick Res

### Downloads
- [Dropbox](http://dropbox.com)
- [Alfred](http://www.alfredapp.com)
- Adobe Suite
- 1Password
- Spectacle
- Cyberduck
- Chrome
- Hipchat
- Instashare
- Skype
- Spotify

### Xcode
- Downloads > Command Line Tools

===
After Dropbox
### Dropbox Apps
- Font Explorer
- TextMate

===
After Xcode (sequentially)
- Homebrew
- Github
- Ruby
- Rails
- Postgis
- Postgres
- Imagemagik

===
After Github
- Spire
- MLS
- TM Bundles

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
