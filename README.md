# Environment

## General

### Developer

- [Insomnia - Cross-platform REST API Client](https://insomnia.rest/)
- [GCloud SDK](https://cloud.google.com/sdk/downloads)
- [Docker](https://www.docker.com/get-started)
- [Github CLI](https://cli.github.com/)
- [Tableplus - Database management](https://www.tableplus.com/)

#### Editor

- [Visual Studio Code](https://code.visualstudio.com/)
- [GoLand](https://www.jetbrains.com/go/)
- [PyCharm](https://www.jetbrains.com/pycharm/)

VS Code Sync Plugins and settings: (CMD+Shift+P) `Settings Sync: Turn On ...` 

##### Editor Font

- https://www.jetbrains.com/lp/mono/
- https://www.monolisa.dev/
- https://sourcefoundry.org/hack/
- https://www.programmingfonts.org/
- https://github.com/chriscoyier/coding-fonts
- https://developer.apple.com/fonts/
- https://devfonts.gafi.dev/
- https://github.com/mona-sans

#### Terminal

- [Warp - Rust-based](https://www.warp.dev/)

Install first the [Oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) and then [Space Prompt](https://github.com/denysdovhan/spaceship-prompt).

Installing Space Prompt: https://spaceship-prompt.sh/getting-started/ 


#### Settings

```shell
git config --global user.name "NAME"
git config --global user.email "EMAIL"
git config --global color.ui true
```

### Design

- [Figma](https://www.figma.com/downloads/)
- :apple: [Affinity Designer](https://affinity.serif.com/en-us/designer/)
- :apple: [Affinity Photo](https://affinity.serif.com/en-us/photo/)

### Miscellaneous

- [1Password](https://1password.com/)
- [Spotify](https://www.spotify.com/ca-en/download/other/)
- [Discord](https://discord.com/download)
- [CleanShot X - Capture your Mac’s screen like a pro](https://getcleanshot.com/)
- [Raycast - Supercharged productivity](https://www.raycast.com/)

### Browsers

- [Google Chrome](https://www.google.ca/chrome/)
- [Mozilla Firefox](https://www.mozilla.org/en-CA/firefox/new/)

### Video

- [DaVinci](https://www.blackmagicdesign.com/products/davinciresolve)

## :apple: Mac

Install Homebrew: https://brew.sh/

- Mac already have ZSH

### Languages

#### Go

```shell
brew install go
```

https://github.com/rakyll/govalidate

#### Node

**FNM - Node.js version manager, built in Rust**

https://github.com/Schniz/fnm

**NVM**

```shell
brew install nvm
```

**Node 16**

```shell
nvm install 16
```

### Utilities

Capture your screen
- [An open-source screen recorder built with web technology - KAP](https://getkap.co/)
- [Prevent your Mac from falling asleep, dimming the screen or starting your screensaver - Theine](https://apps.apple.com/app/theine/id955848755?mt=12)

### MySQL

https://dev.mysql.com/downloads/file/?id=466265

The Oracle installer for MySQL puts the mysql binary in /usr/local/mysql/bin. You either need to call it with the full path:

```shell
/usr/local/mysql/bin/mysql
```
Or put /usr/local/mysql/bin in your PATH by adding the following to end of your ~/.bash_profile or ~/.profile:

```shell
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

#### Postgres

```shell
brew install postgres
```

- Postico 2 - https://eggerapps.at/postico2/ - The native Mac app for PostgreSQL


## Ubuntu

Ubuntu + Terminator + Oh My ZSH with Agnoster Theme
https://gist.github.com/renshuki/3cf3de6e7f00fa7e744a

zsh
https://gist.github.com/tsabat/1498393

http://superuser.com/questions/1114732/how-do-i-install-oh-my-zsh-with-a-custom-zsh-install

```shell script
git clone --depth=1 https://github.com/robbyrussell/oh-my-zsh.git $HOME/.oh-my-zsh
cp $HOME/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```

### Java
https://www.digitalocean.com/community/tutorials/como-instalar-o-java-com-apt-get-no-ubuntu-16-04-pt

### Node (without sudo)

1. First install node through pkg
https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions

2. Change permissions 
https://docs.npmjs.com/getting-started/fixing-npm-permissions
