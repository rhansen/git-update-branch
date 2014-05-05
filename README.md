git-update-branch
=================

Synopsis
--------

    git-update-branch [options] [--] [<branch>...]

Description
-----------

Performs a fast-forward update of the given branches to the upstream
tracking branch.  If no branches are specified, the current branch is
updated.

Options
-------

  * `-h`, `--help`:  Print a usage message and exit.
  * `-a`, `--all`:  Update all local branches (no branch arguments may
    be given).
  * `-q`, `--quiet`:  Don't print log messages.
  * `--`:  Treat the remaining arguments as branch names.
