# phpstorm-live-templates

# Installation
1. Backup your old phpstorm live templates directory:
```
// OSX
PHPSTORM_VERSION=2018.2

mv ~/Library/Preferences/PhpStorm${PHPSTORM_VERSION}/templates ~/Library/Preferences/PhpStorm${PHPSTORM_VERSION}/templates.bak
```

2. Clone this repo:
```
git clone git@github.com:raw34/phpstorm-live-templates.git ~/.phpstorm
```

3. Install this repo:
```
ln -s ~/.phpstorm/templates ~/Library/Preferences/PhpStorm${PHPSTORM_VERSION}/templates
```
