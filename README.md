genesis
=======

## Reinstall checklist
In sequential order with breaks for dependencies

### App Store
- Alfred
- Cloud
- Color Snapper
- Sparrow

### Downloads
- Adobe Suite
- 1Password
- Quick Res
- Spectacle
- Dropbox
- Cyberduck
- Chrome
- Hipchat
- Instashare
- LiveReload
- Mock SMTP
- Skype
- Spotify

### System
- Xcode

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
'''
alias spire="cd ~/code/spire"
alias profile="mate ~/.profile"
alias mls="cd ~/code/mls"
alias bundles="cd ~/Library/Application\ Support/TextMate/Bundles/"
eval "$(hub alias -s)"
export PATH="/usr/local/bin:/usr/local/opt/ruby/bin:/Developer/usr/bin:/usr/local/sbin:/usr/local/mysql/bin:~/bin:$PATH"
### Added by the Heroku Toolbelt
export PATH="/usr/local/heroku/bin:$PATH"
'''
