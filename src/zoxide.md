# Zoxide

repo: https://github.com/ajeetdsouza/zoxide

## Installation

For zoxide itself
`cargo install zoxide --locked`

For fzf
`sudo apt install fzf`

Within `.zshrc`

```zsh 
eval "$(zoxide init --cmd cd zsh)"
```

Note that this will allow for the use of `cd` as normal, so that on systems that do not have zoxide installed, cd muscle memory is maintained.

## Use

```bash
z foo              # cd into highest ranked directory matching foo
z foo bar          # cd into highest ranked directory matching foo and bar
z foo /            # cd into a subdirectory starting with foo

z ~/foo            # z also works like a regular cd command
z foo/             # cd into relative path
z ..               # cd one level up
z -                # cd into previous directory

zi foo             # cd with interactive selection (using fzf)

z foo<SPACE><TAB>  # show interactive completions (zoxide v0.8.0+, bash 4.4+/fish/zsh only)
```

## Linked Documentation
Youtube video: https://www.youtube.com/watch?v=aghxkpyRVDY

