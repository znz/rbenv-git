# rbenv-git

This is an [rbenv](https://github.com/sstephenson/rbenv) plugin that
provides `rbenv git` command to run `git` in directories of rbenv
and all installed plugins.

## Installation

Simply clone the repository into the plugins directory:

    mkdir -p $(rbenv root)/plugins
    git clone https://github.com/znz/rbenv-git.git $(rbenv root)/plugins/rbenv-git

## Usage

Update rbenv and all installed plugins:

    rbenv git pull

Housekeeping:

    rbenv git gc

Show all remote repositories:

    rbenv git remote -v

Show statuses:

    rbenv git status

And you can use any git sub commands.

## License

(The MIT License)


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/znz/rbenv-git/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

