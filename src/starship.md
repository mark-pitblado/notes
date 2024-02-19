# Starship

Starship is a fast command line prompt written in rust, compatible with bash, zsh and powershell (plus others)

## Installtion

To install, you may use cargo or install directly using a `.sh` file.

```zsh
cargo install starship --locked
```

## Use

Simply place the following at the bottom of the `.zshrc` (or `.bashrc` etc) and reload the terminal.

```zsh
eval "$(starship init zsh)"
```

## Configuration

Create the configuration directory

```zsh
mkdir -p ~/.config && touch ~/.config/starship.toml
```

Then make any cofiguration changes desired in that `.toml` file.
