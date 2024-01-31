# How to setup a GPG key in Git

This page is going to assume that a key has already been created on the system and added to GitHub through the web interface.

To set the list of keys on the system

```zsh
gpg --list-secret-keys --keyid-format=long
```

To configure git to use the key

```zsh
git config --global user.signingkey <keyid-from-step-above>
```

To set git to sign commits by default

```zsh
git config --global commit.gpgsign true
```

To add the key to the `.zshrc` (or `.bashrc`)

```zsh
#In ~/.zshrc
export GPG_TTY=$(tty)
```
