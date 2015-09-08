Dotfiles
========
Personal dotfile based on Anish Athalye dotfiles, released under the MIT License. See
[LICENSE.md][license]

[dotbot]: https://github.com/anishathalye/dotbot



Original instructions
======================
Run `install` to automatically set up the development
environment. Note that the install script is idempotent: it can safely be run
multiple times.

Dotfiles uses [Dotbot][dotbot] for installation.

Making Local Customizations
---------------------------

You can make local customizations for some programs by editing these files:

* `vim` : `~/.vimrc_local`
* `zsh` : `~/.zshrc_local_before` run before `.zshrc`
* `zsh` : `~/.zshrc_local_after` run after `.zshrc`
* `git` : `~/.gitconfig_local`
* `hg` : `~/.hgrc_local`
* `tmux` : `~/.tmux_local.conf`

License
-------

Copyright (c) 2013-2015 Anish Athalye. Released under the MIT License. See
[LICENSE.md][license] for details.

[dotbot]: https://github.com/anishathalye/dotbot
[license]: LICENSE.md
