
# [Neo vim](https://neovim.io/)


## Inspired by

https://github.com/NeuralNine/config-files/blob/master/arch_linux/init.vim

https://youtu.be/JWReY93Vl6g


## Setup

1. Install Neovim

https://github.com/neovim/neovim/wiki/Installing-Neovim

2. Config Neovim file

```bash
git clone https://github.com/zeroest/config.git
cd nvim

mkdir -p ~/.config/nvim
mv ./init.vim ~/.config/nvim
```

3. Set Plugin 

https://github.com/junegunn/vim-plug

Show in [Installation](https://github.com/junegunn/vim-plug#installation)

```bash
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

4. Install Plugin

Show in [Commands](https://github.com/junegunn/vim-plug#commands)

```bash
:PlugInstall
```

## Done


