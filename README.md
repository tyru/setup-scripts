
# SYNOPSIS
## setup
Let's set up my environment.

    $ /path/to/setup

## git-clone-dotfiles
git-clone `git://github.com/tyru/dotfiles.git`
and set up misc. info.

    $ cd ~/git
    $ /path/to/git-clone-dotfiles

## git-clone-github-repos
Mirror all github repos to `~/git/github`, `~/git/+public/github`.

    $ /path/to/git-clone-github-repos

## mirror-all-github-repos
Mirror all github repos.

    $ cd ~/git/+public    # git-daemon server
    $ /path/to/mirror-all-github-repos --bare

    $ cd ~/git    # for development
    $ /path/to/mirror-all-github-repos
