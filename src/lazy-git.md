# lazygit

> [repository](https://github.com/jesseduffield/lazygit)

Lazygit allows the use of a terminal user interface to perform git operations.

## Installation

This can be used to install on Ubuntu

```zsh
LAZYGIT_VERSION=$(curl -s "https://api.github.com/repos/jesseduffield/lazygit/releases/latest" | grep -Po '"tag_name": "v\K[^"]*')
curl -Lo lazygit.tar.gz "https://github.com/jesseduffield/lazygit/releases/latest/download/lazygit_${LAZYGIT_VERSION}_Linux_x86_64.tar.gz"
tar xf lazygit.tar.gz lazygit
sudo install lazygit /usr/local/bin
```

## Commands

Instead of listing all the commands here, it is much easier to use `?` from within the lazygit interface. This brings up the shortcuts for all keys. I will cover the top ones that I use.

| Command | Description |
| ------- | ----------- |
| `<space>` | adds/removes the file current selected |
| `c` | commit, brings up interface to add message |
| `p` | git pull |
| `P` | git push | 
