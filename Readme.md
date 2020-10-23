### Install and set up zsh as default
***1. Install zsh***
```sh
 $ sudo apt install zsh
```
***2. check zsh version***
```sh
zsh --version
```
***3. Make it your default shell:***
```sh
 $ chsh -s $(which zsh)
```

***4 - A . Install oh-my-zsh via curl:***
```sh
 $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

***4 - B . Install oh-my-zsh via wget:***
```sh
 $ sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

***5. Restart computer:***

### Plugins
***Go to .zshrc file then add plugns***
```plugins=(git ....)```

Plugns link | [https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins][PlDb]


### Themes

In order to enable a theme, set ZSH_THEME to the name of the theme in your ~/.zshrc, before sourcing Oh My Zsh; for example: ZSH_THEME=robbyrussell If you do not want any theme enabled, just set ZSH_THEME to blank: ZSH_THEME=""
Themes link | [https://github.com/ohmyzsh/ohmyzsh/wiki/Themes][PlDb]

### My favorite theme
```power level 10k```
Themes link | [https://github.com/romkatv/powerlevel10k][PlDb]