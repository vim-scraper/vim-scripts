---
layout: default
title: Tools
comments: true
---

## Tools

These projects work closely with the vim-scripts.org mirror:

 * [vundle](http://github.com/gmarik/vundle) makes it easy to find
   and install plugins without ever leaving the Vim environment.
 * [vim-update-bundles](http://github.com/bronson/vim-update-bundles)
   is a small Ruby script that reads your .vimrc to determine which plugins
   you want, then installs and removes plugins to match.
 * [vimmer](https://github.com/densitypop/Vimmer) is a command-line utility
   and Ruby gem to install, update and remove Vim plugins.
 * Also see the alternatives below.  They don't use the mirror but
   some of them make downloading scripts much easier.

These projects help manage the plugins once they're downloaded:

 * [Pathogen](http://github.com/tpope/vim-pathogen) and its lightweight alternative
   [Unbundle](http://github.com/sunaku/vim-unbundle) allow you to store your scripts
   individually in `~/.vim/bundle/` instead of one gigantic communal directory tree.
 * [tplugin](http://github.com/tomtom/tplugin_vim)
   can be thought of as a mix of Pathogen and
   [AsNeeded](http://github.com/vim-scripts/AsNeeded).

### Manual

Less software is more.  If you want to manage your plugins
by hand, here are some docs.

 * [A screencast](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/)
   showing how to manage plugins manually using Pathogen and git submodules.
 * [The Modern Vim Config with Pathogen](http://tammersaleh.com/posts/the-modern-vim-config-with-pathogen),
   a blog post by Tammer Saleh.

### Alternatives

These perform their own package management instead of using the
vim-scripts.org mirror.

 * [vim-addon-manager](http://github.com/MarcWeber/vim-addon-manager)
   is a package manager written 100% in VimL.
 * [Janus](http://github.com/carlhuda/janus) is a collection of plugins but
   does include its own plugin manager.
 * [Vimpire](https://bitbucket.org/sharat87/vimpire) reads bundle tags
   from .vimrc and updates plugins to match.  Written in Python, supports Mercurial.
 * [Vimana](http://github.com/c9s/Vimana) is a Perl-based package manager.
 * [jolt](http://github.com/vimjolts/jolt)
    Vim Package Management written in python
 * [vim-nicktears](http://github.com/carllerche/vim-nicktears) manages
   Vim plugins using [Rubygems](http://rubygems.org/).
 * [Vim Script Updater](http://www.vim.org/scripts/script.php?script_id=3135)
   manages plugins using Python.
 * [GetLatestVimScripts](http://www.vim.org/scripts/script.php?script_id=642)
   is a 100% VimL solution.

Also see the [question on StackOverflow](http://stackoverflow.com/questions/2458398/package-management-for-vim).
