# Plugin Managers

Today I learned that vim has two main plugin managers:

1. Tim Pope<sup>1</sup>'s [Pathogen][1]
1. gmarik's [Vundle][2]

Basically, the only difference is in the way each installs
the plugins. You can install plugins manually without either manager.

The biggest difference is that with Pathogen, you have to clone
and install plugins on the filesystem manually. With Vundle,
you add directives to your `~/.vimrc` and run a command
to install/update the plugins, thus abstracting vim's away
how vim's plugin system works.

Both plugin managers are also plugins. Yeah.

--

**Footnotes**

1. Tim Pope is kind of a vim legend, from what I gather.

[1]: https://github.com/tpope/vim-pathogen
[2]: https://github.com/gmarik/Vundle.vim
