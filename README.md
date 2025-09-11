# Environment

## General

Guide: [Set up a Mac in 2024 for Power Users and Developers](https://www.youtube.com/watch?v=GK7zLYAXdDs)

### Inspiration

- [My Minimal MacBook Pro Setup Guide](https://eugeneyan.com/writing/mac-setup/)
- [Setting up new M3 Max MacBook Pro for Full-Stack Web Development](https://www.youtube.com/watch?v=PvU_aEgIjSg)
- [7 Amazing CLI Tools You Need To Try](https://www.youtube.com/watch?v=mmqDYw9C30I)

### Developer

- [Yaak - The API client for modern developers](https://yaak.app/)
- [Bruno - Opensource IDE For Exploring and Testing Api's](https://www.usebruno.com/)
- [Docker](https://www.docker.com/get-started)
- [Github CLI](https://cli.github.com/)
- [Tableplus - Database management](https://www.tableplus.com/) - Paid
- [PgAdmin 4](https://www.pgadmin.org/download/) - Free - Open source
  - `brew install --cask pgadmin4`
- [Raycast](https://www.raycast.com/)

#### Editor

- [Zed](https://zed.dev/)
- [Fleet](https://www.jetbrains.com/fleet/)
- [Visual Studio Code](https://code.visualstudio.com/)
  - [Vitesse Theme](https://marketplace.visualstudio.com/items?itemName=antfu.theme-vitesse)
  - [White - Minimalist monochrome theme](https://marketplace.visualstudio.com/items?itemName=arthurwhite.White)
  - [Batsignal Theme](https://github.com/natew/batsignal)
  - [Carbon Product Icons](https://marketplace.visualstudio.com/items?itemName=antfu.icons-carbon)
  - [Railly Hugo](https://marketplace.visualstudio.com/items?itemName=RaillyHugo.one-hunter)
  - [Malibu](https://marketplace.visualstudio.com/items?itemName=wicked-labs.malibu)
- [GoLand](https://www.jetbrains.com/go/)
- [PyCharm](https://www.jetbrains.com/pycharm/)

VS Code Sync Plugins and settings: (CMD+Shift+P) `Settings Sync: Turn On ...`

## My Terminal: Ghostty + Nerd Font + Custom ZSH: Spaceship + Theme: Starship

![my terminal](./terminal.png)

- Install [Ghostty](https://ghostty.org/)
- Install [Geist Mono Nerd Font - Patched fonts](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/GeistMono)
  - [Geist Mono](https://vercel.com/font)
  - Set up the font family in [Ghostty](https://ghostty.org/docs/config#configuration-format): `font-family = "GeistMono Nerd Font Mono"`
- Install [Spaceship prompt](https://spaceship-prompt.sh/)
  - `brew install spaceship`
  - `echo "source $(brew --prefix)/opt/spaceship/spaceship.zsh" >>! ~/.zshrc`
- Install [Starship](https://starship.rs/)
  - `brew install starship`
  - Add the following to the end of `~/.zshrc`:
    - `eval "$(starship init zsh)"`
  - [Gruvbox Rainbow Preset](https://starship.rs/presets/gruvbox-rainbow)
    - `starship preset gruvbox-rainbow -o ~/.config/starship.toml`

### Utilities

- https://github.com/zsh-users/zsh-autosuggestions (Fish-like autosuggestions for zsh)
  - `brew install zsh-autosuggestions`
  - Add the following to the end of `~/.zshrc`:
    - `source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh`
- https://github.com/zsh-users/zsh-syntax-highlighting (Fish shell like syntax highlighting for Zsh)
  - `brew install zsh-syntax-highlighting`
  - Add the following to the end of `~/.zshrc`
    - `source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh`
- https://github.com/nvbn/thefuck (Magnificent app which corrects your previous console command)
  - `brew install thefuck`
- https://github.com/junegunn/fzf (A command-line fuzzy finder)
  - `brew install fzf`
  - Add the following to the end of `~/.zshrc`:
    - `source <(fzf --zsh)`
- https://github.com/sharkdp/fd (A simple, fast and user-friendly alternative to 'find')
  - `brew install fd`
- https://github.com/eza-community/eza (A modern, maintained replacement for ls, written in rust)
  - `brew install eza`
- https://github.com/ajeetdsouza/zoxide (A smarter cd command. Supports all major shells)
  - `brew install zoxide`
  - Add the following to the end of `~/.zshrc`:
    - `eval "$(zoxide init zsh)"` 

##### Editor Font

- https://github.com/ryanoasis/nerd-fonts
- https://input.djr.com/
- https://www.jetbrains.com/lp/mono/
- https://www.monolisa.dev/
- https://sourcefoundry.org/hack/
- https://www.programmingfonts.org/
- https://github.com/chriscoyier/coding-fonts
- https://developer.apple.com/fonts/
- https://devfonts.gafi.dev/
- https://github.com/mona-sans
- https://github.com/intel/intel-one-mono
- https://brailleinstitute.org/freefont
- https://monaspace.githubnext.com/
- https://vercel.com/font

#### Terminal

- [iTerm2](https://iterm2.com/)
- [Warp - Rust-based](https://www.warp.dev/)
- [Nushell](https://www.nushell.sh/)

#### Command line

- [Fish](https://fishshell.com/)

First, install the [Oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).

*Zsh theme*
- [PowerLevel10k](https://github.com/romkatv/powerlevel10k)
- [Space Prompt](https://github.com/denysdovhan/spaceship-prompt)



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

#### Security 
- [1Password](https://1password.com/)
  - [CLI](https://developer.1password.com/docs/cli/get-started/)

#### Productivity
- [CleanShot X - Capture your Mac’s screen like a pro](https://getcleanshot.com/)
- [Raycast - Supercharged productivity](https://www.raycast.com/)
  - Brew
  - TailwindCSS
  - 1Password
  - Spotify
  - VSCode
- [Screen Studio - Beautiful screen recordings in minutes](https://www.screen.studio/)

#### Others
- [Spotify](https://www.spotify.com/ca-en/download/other/)
- [Discord](https://discord.com/download)
- [Hidden Bar](https://github.com/dwarvesf/hidden)
- [AltTab](https://alt-tab-macos.netlify.app/)
- [An open-source screen recorder built with web technology - KAP](https://getkap.co/)
- [Prevent your Mac from falling asleep, dimming the screen or starting your screensaver - Theine](https://apps.apple.com/app/theine/id955848755?mt=12)


### Browsers

- [Google Chrome](https://www.google.ca/chrome/)
- [Mozilla Firefox](https://www.mozilla.org/en-CA/firefox/new/)

### Video

- [DaVinci](https://www.blackmagicdesign.com/products/davinciresolve)

## :apple: Mac

Install Homebrew: https://brew.sh/

- Mac already has ZSH

### Languages

#### Go

```shell
brew install go
```

https://github.com/rakyll/govalidate

#### Node

**FNM - Node.js version manager, built-in Rust**

https://github.com/Schniz/fnm

```shell
brew install fnm
```

**NVM**

```shell
brew install nvm
```

**Node 20**

```shell
nvm install 20
nvm alias default 20
```

#### Ruby

**Rbenv**

```shell
brew install rbenv
```

**Ruby 3.3.6**

```shell
rbenv install 3.3.6
rbenv global 3.3.6
```

#### Postgres

```shell
brew install postgres
```

- PgAdmin 4 (Free - Open source) - https://www.pgadmin.org/download/pgadmin-4-macos/
- Postico 2 - https://eggerapps.at/postico2/ - The native Mac app for PostgreSQL
