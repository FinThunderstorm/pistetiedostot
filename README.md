# pistetiedostot

Clone this repository to `~/Configurations/pistetiedostot`, then link the configuration files:

```sh
ln -s "$HOME/Configurations/pistetiedostot"/{.gitconfig,.gitignore_global,.tmux.conf,.vimrc,.zprofile,.zshrc} "$HOME/"
```

If any destination files already exist, back them up before creating the links.
The linked `.zshrc` loads `.zsh.conf` and `.dev.conf` directly from the repository, so those files need no symlinks.
