# Gitconfig

[git](/git.md) is configured with `.gitconfig` files.
The main configuration file is located at `~/.gitconfig`.
The `.gitconfig` file stores all [git](/git.md) configuration like a `user.name` and `user.email` that is used for each commit.
It also stores custom aliases and branch handling preferences.

Every [git](/git.md) repository contains a `.git/config` file, which can be used to overwrite values specified in the default `~/.gitconfig` file.

> [!TIP]
> It is recommended to put all `.gitconfig` files in the [dotfiles](/dotfiles.md).
> This will make sure the [git](/git.md) configuration is backed up.