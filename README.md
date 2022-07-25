# vim-latex aka latex-suite

This vim plugin provides a rich tool of features for editing latex files.
For further descriptions, we refer to the [website][web].
There is also a [user manual][man]. 
and a [beginner's tutorial][tut].

This a fork of the main [repository][vimlatex]. 
Its purpose is to fix an issue with a conflicting keymap binding of `<C-j>` used
in vim-latex, but also in many other common vim plugins (e.g.
[vim-tmux-navigator][vtn]).

## Installation

We recommend the installation via a plugin manager such as
[pathogen](https://github.com/tpope/vim-pathogen),
[Vundle](https://github.com/gmarik/vundle), or
[vim-plug][vimplug].

Instructions for manual installation is documented at the [website][downl].

Recommended settings after installation can be found in [Section 1][recset]
of the manual.

## Documentation

As already mentioned, the manual can be found [here][man].
After installation, you will also have a rich in-vim documentation, see
`:help latex-suite`.


[web]: http://vim-latex.sourceforge.net/
[man]: http://vim-latex.sourceforge.net/index.php?subject=manual&title=Manual#user-manual
[tut]: http://vim-latex.sourceforge.net/index.php?subject=manual&title=Tutorial#tutorial
[vimplug]: https://github.com/junegunn/vim-plug
[downl]: http://vim-latex.sourceforge.net/index.php?subject=download
[recset]: http://vim-latex.sourceforge.net/documentation/latex-suite.html#recommended-settings
[vimlatex]: https://github.com/vim-latex/vim-latex
[vtn]: https://github.com/christoomey/vim-tmux-navigator
