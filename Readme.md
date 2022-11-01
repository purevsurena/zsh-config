### Install and set up zsh as default

**_1. Install zsh_**

```sh
 $ sudo apt install zsh
```

**_2. check zsh version_**

```sh
zsh --version
```

c
**_3. Make it your default shell:_**

```sh
 $ chsh -s $(which zsh)
```

**_4 - A . Install oh-my-zsh via curl:_**

```sh
 $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

**_4 - B . Install oh-my-zsh via wget:_**

```sh
 $ sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

**_5. Restart computer:_**

### Plugins

**_Go to .zshrc file then add plugns_**
`plugins=(git ....)`

Plugns link | https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins

### Themes

In order to enable a theme, set ZSH_THEME to the name of the theme in your ~/.zshrc, before sourcing Oh My Zsh; for example: ZSH_THEME=robbyrussell If you do not want any theme enabled, just set ZSH_THEME to blank: ZSH_THEME=""
Themes link | https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

### My favorite theme

`power level 10k`
Themes link | https://github.com/romkatv/powerlevel10k
