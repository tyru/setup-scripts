
# SYNOPSIS
## setup
Let's set up my environment.

    $ /path/to/setup

`setup` will set up new environment *if it doesn't exist*.
but *if it exists*, `setup` will *update* environment.
This means it can be safe even if I add it to cron jobs.


# DIRECTORIES
## local-lib
Install local::lib.

## cpanminus
Install cpanminus.

## cpan-outdated
Install cpan-outdated.

## symlinks
Create symlinks.

## git-clone-dotfiles
git-clone `git://github.com/tyru/dotfiles.git`
and set up misc. info.

## git-clone-github-repos
Mirror all github repos to `~/git/github`, `~/git/+public/github`.

## TODO
- cron
