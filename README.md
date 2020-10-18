# Environment

## General

### Editor

- [Visual Studio Code](https://code.visualstudio.com/)
- [GoLand](https://www.jetbrains.com/go/)
- [PyCharm](https://www.jetbrains.com/pycharm/)

#### Visual Studio Code

- Sync Plugins and settings: (CMD+Shift+P) `Settings Sync: Turn On ...` 

#### Editor Font

- https://www.jetbrains.com/lp/mono/
- https://www.monolisa.dev/
- https://sourcefoundry.org/hack/

### Terminal

- [Oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- [Space Prompt](https://github.com/denysdovhan/spaceship-prompt)


### Tools

- [1Password](https://1password.com/)
- [Insomnia - Cross-platform REST API Client](https://insomnia.rest/)
- [GCloud SDK](https://cloud.google.com/sdk/downloads)


# Ubuntu

Ubuntu + Terminator + Oh My ZSH with Agnoster Theme
https://gist.github.com/renshuki/3cf3de6e7f00fa7e744a

zsh
https://gist.github.com/tsabat/1498393

http://superuser.com/questions/1114732/how-do-i-install-oh-my-zsh-with-a-custom-zsh-install

```
git clone --depth=1 https://github.com/robbyrussell/oh-my-zsh.git $HOME/.oh-my-zsh
cp $HOME/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```

## Java
https://www.digitalocean.com/community/tutorials/como-instalar-o-java-com-apt-get-no-ubuntu-16-04-pt

# Mac
brew
http://brew.sh/

Ruby
https://gorails.com/setup/osx/10.12-sierra

iTerm2
https://www.iterm2.com/

Customize - Solarized Dark
http://yoderbacon.com/blog/2014/10/22/how-to-customize-iterm/

iTerm2 + Oh My Zsh + Solarized color scheme + Meslo powerline font (choose Meslo LG L DZ Regular for Powerline)
https://gist.github.com/kevin-smets/8568070

## Utilities

Capture your screen
https://getkap.co/
https://getcleanshot.com/

### Node (without sudo)

1. First install node through pkg
https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions

2. Change permissions 
https://docs.npmjs.com/getting-started/fixing-npm-permissions

### Yarn 
https://yarnpkg.com/en/docs/install

### MySQL

https://dev.mysql.com/downloads/file/?id=466265

The Oracle installer for MySQL puts the mysql binary in /usr/local/mysql/bin. You either need to call it with the full path:
```
/usr/local/mysql/bin/mysql
```
Or put /usr/local/mysql/bin in your PATH by adding the following to end of your ~/.bash_profile or ~/.profile:
```
export PATH=/usr/local/mysql/bin:${PATH}
```

Change password root:
MySQL 5.7.6 and later:
```
ALTER USER 'root'@'localhost' IDENTIFIED BY 'MyNewPass';
```
MySQL 5.7.5 and earlier:
```
SET PASSWORD FOR 'root'@'localhost' = PASSWORD('MyNewPass');
```

### Go

Config your bash with (ex: ~/.zshrc or ~/.bash_profile)

```bash
export GOPATH=$HOME/go
export GOBIN=$GOPATH/bin
export PATH=$PATH:$GOBIN
```

https://github.com/rakyll/govalidate
