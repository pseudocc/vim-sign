# VIM SIGN

Vim plugin that inserts your signiture on insert mode.

Something like this:

    `Atlas Yu <atlas.yu@canonical.com>`

## Installation

copy `plugin/sign.vim` to `~/.vim/plugin`

## Usage

Set the user name and email for Git or Debian before using this plugin.

- Ctrl+s,d

    Insert $DEBFULLNAME and $DEBEMAIL.

- Ctrl+s,g

    Insert `$(git config user.name)` and `$(git config user.email)`
