# bitbucket-git-helpers

Some git helper scripts for dealing with repos on bitbucket.

## Contents

* git-bb-open - Opens the current directory (or a path if specified) on bitbucket in the current branch.

## Installing

### Antigen

If you're using [Antigen](https://github.com/zsh-users/antigen):

1. Add `antigen bundle unixorn/bitbucket-git-helpers` to your `.zshrc` where you've listed your other plugins.
2. Close and reopen your Terminal/iTerm window to **refresh context** and use the plugin. Alternatively, you can run `antigen bundle unixorn/bitbucket-git-helpers` in a running shell to have antigen load the new plugin.

### oh-my-zsh

If you're using [oh-my-zsh](github.com/robbyrussell/oh-my-zsh):

1. In the command line, change to _oh-my-zsh_'s custom plugin directory :

    `cd ~/.oh-my-zsh/custom/plugins/`

2. Clone the repository into a new `bitbucket-git-helpers` directory:

    `git clone https://github.com/unixorn/bitbucket-git-helpers.git bitbucket-git-helpers`

3. Edit your `~/.zshrc` and add `bitbucket-git-helpers` – same as clone directory – to the list of plugins to enable:

    `plugins=( ... bitbucket-git-helpers )`

4. Then, restart your terminal application to **refresh context** and use the plugin. Alternatively, you can source your current shell configuration:

    `source ~/.zshrc`

### zgen

If you're using [zgen](https://github.com/tarjoilija/zgen):

1. Add `zgen load unixorn/bitbucket-git-helpers` to your `.zshrc` along with your other `zgen load` commands.
2. `rm ${ZGEN_INIT}/init.zsh && zgen save`

### Manual Installation

Nothing here actually requires you to use ZSH or zgen, that's just a convenient distribution method for anyone using a ZSH framework.

If you aren't using any zsh frameworks, or if you're a bash user, do the following steps:

1. git clone this repository
2. Add `cloneDirectory/bin` to your `$PATH`.

