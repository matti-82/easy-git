## Why do we need Easy-Git?
Short Explaination:  
Easy-Git is a command line utility that makes the use of Git easier.

Long Explaination:  
Git is the version-control system that allows the highest flexibility. But its use is very complicated, mainly because the commands don't do what the user expects,
and to get the desired behaviour, many command line options must be passed. Let's have a look at **git pull**: It requires a clean working directory, it does a merge
which leads to a messy history, and it does not resolve merge conflicts automatically. **eg pull** does what most users want: It stashes and restores changes to the
working directory automatically, it does a rebase to have a clean history, and it resolves merge conflicts automatically. Beside pull, Easy-Git supports a couple of
commands that are needed in daily work, e.g. commit, push, log and manage branches. Easy-Git is designed for having at most 1 server per local repository, which is the
case for almost all users. If you want to pull and push from/to multiple servers from a single local repository, you will still need the basic Git.

## Installation
Easy-Git is only available for Linux and Unix. Choose a directory that is in the PATH variable (e.g. /usr/bin) and either copy **eg** there or create a symlink to it.
Make sure that eg has executable permission. That should be the case if you cloned the repo, but if you downloaded the ZIP file the permission must be set manually.  
To get a list of available commands, run eg without parameters.
