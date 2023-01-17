# Git & GitHub

## Git vs. GitHub

* Git is the private local version control repository
* GitHub is the remote shared public version control repository

## Cloning

To make a local copy of a remote repo use `clone` with the URL of the git, e.g. `git clone https://github.com/andrewemorris/reading-notes.git`

## The Process

The Git/GitHub process is:

1. Add (locally to git) e.g. `git add .`
2. Commit (the local changes) e.g. `git commit`
3. Push (the commited changes to the remote GitHub) e.g. `git push -f`

## Notes

* Each time file is updated it needs to be added
* git push -f firces local to overwrite remote (i.e. when remote not in sync and wna tto overweite it)
* git status summarieses the differences between local and remote
