# Bash Dotfiles & Configuration Files

These files are _primarily used on MacOS_. As such there will be some minor differences that need to be accounted for if used on Linux.

## Install Instructions

If you're bothered, then remove/backup your existing dotfiles.

```sh
mv $HOME/.bashrc $HOME/.bashrc_old
mv $HOME/.vimrc $HOME/.vimrc_old
mv $HOME/.tmux.conf $HOME/.tmux.conf.old
```

Then create symbolic links in the `home` directory that links to each dotfile.

```sh
ln -s $HOME/<path-to-repo>/dotfiles/bashrc $HOME/.bashrc
ln -s $HOME/<path-to-repo>/dotfiles/vimrc $HOME/.vimrc
ln -s $HOME/<path-to-repo>/dotfiles/tmux.conf $HOME/.tmux.conf
```

