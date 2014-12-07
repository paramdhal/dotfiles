Dotfiles
========

My collection of dotfiles

To install clone into home directory. Dotfiles are symlinked from the dotfiles directory into into the home dircetory.Old files will be placed in a dotfiles_old directory.

```bash
git clone https://github.com/paramdhal/dotfiles.git && cd dotfiles && ./makesymlinks.sh
```

Create a gitconfig.local file in the dotfiles directory for local config such as name and difftools etc.

```bash
[user]
    name = Param Dhaliwal
    email = paramdhal@gmail.com
[credential]
    helper = osxkeychain

# if using git 2.0
[push]
	default = simple

```
