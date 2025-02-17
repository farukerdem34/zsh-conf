<div align="center">

![](https://img.shields.io/badge/tmux-1BB91F?style=for-the-badge&logo=tmux&logoColor=white) ![](https://img.shields.io/badge/Zsh-F15A24?style=for-the-badge&logo=Zsh&logoColor=white) ![](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=GNU%20Bash&logoColor=white) ![](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white) ![](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=apple&logoColor=white) ![](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) 
</div>


![](assets/1.png)

![](assets/2.png)

![](assets/3.png)

![](assets/4.png)

# Dependecies

```bash
sudo apt update -y;sudo apt upgrade -y;sudo apt install stow neovim tmux bat fzf git gcc -y
```

```bash
sudo pacman -Syu --noconfirm --color always stow neovim tmux bat fzf git gcc btop
```

# Dotfiles

```bash
git clone https://github.com/farukerdem34/dotfiles.git $HOME/.dotfiles
cd $HOME/dotfiles/
stow bat fastfetch kitty nvim tmux vimrc zsh
~/.tmux/plugins/tpm/bin/install_plugins
nvim --headless "+Lazy! sync" +qa
. ~/.zshrc
```

## For Desktop Users

```bash
git clone https://github.com/farukerdem34/dotfiles.git ~/.dotfiles
cd ~/.dotfiles/
bash init-user.sh

```

## For Servers

```bash
git clone https://github.com/farukerdem34/dotfiles.git ~/.dotfiles
cd ~/.dotfiles/
bash init-server.sh
```
