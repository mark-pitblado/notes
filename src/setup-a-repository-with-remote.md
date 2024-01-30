# Taking a local repository and publishing it 

There are two basic steps.
1. The remote location needs to be created
2. The remote location needs to be setup as the remote origin for the local repository.


## Creating a new repository on GitHub
Creating a new repository on Github can be done through the GUI. There is no need to setup a README.md, license etc, however a description can be added since this is not part of the repo itself.

## Linking the local repository to the newly created GitHub repo
If the directory has not already been initialized with git, then running `git init` is needed. The commit message can of course be anything, but init seems somewhat standardized. Note that if a README.md or LICENSE.md was created, the `-f` (force) may be required on `git push`.

```zsh
git init
git add -A
git commit -m 'init'
git remote add origin https://github.com/mark-pitblado/notes.git 
git push -u origin main
```
The above uses https to connect, however if ssh is desired, then the link would be replaced with something like git@github.com:mark-pitblado/notes.git.
