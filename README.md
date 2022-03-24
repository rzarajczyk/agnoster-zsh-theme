# agnoster.rzarajczyk.zsh-theme

Original theme at https://github.com/agnoster/agnoster-zsh-theme

## Changes in comparison to the original Agnoster:
 * displaying git `user.name` in the prompt (moreover, if it is equal to the `$DEFAULT_USER` then an emoji 🧑 is shown). This is especially helpful if you use different git usernames in different projects.
 * directory path is truncated to last two directories, to avoid too long prompt
 * [BUGFIX] no error message when the current directory is `.git`

## Installation
1. copy `agnoster.rzarajczyk.zsh-theme` from https://github.com/rzarajczyk/agnoster-zsh-theme into `$ZSH_CUSTOM/themes` folder.
2. in `~/.zshrc` choose custom agnoster theme:`ZSH_THEME="agnoster.rzarajczyk"`
