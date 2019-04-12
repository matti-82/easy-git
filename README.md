## Why do we need Easy-Git?
Short Explaination:  
Easy-Git is a command line utility that makes the use of Git easier.

Long Explaination:  
Git is the version-control system that allows the highest flexibility. But its use is very complicated, mainly because the commands don't do what the user expects,
and to get the desired behaviour, many command line options must be passed. Lets have a look at **git pull**: It requires a clean working directory, it does a merge
which leads to a messy history, and it does not resolve merge conflicts automatically. **eg pull** does what most users want: It stashes and restores changes to the
working directory automatically, it does a rebase to have a clean history, and it resolves merge conflicts automatically. Beside pull, Easy-Git supports a couple of
commands that are needed in daily work, e.g. commit, push, log and manage branches. Easy-Git is designed for having at most 1 server per local repository, which is the
case for almost all users. If you want to pull and push from/to multiple servers from a single local repository, you will still need the basic Git.

## Installation
Make the file **eg** executable and create a symlink in a directory that is in the PATH variable, e.g. /usr/bin  
To get a list of available commands, simply run eg without parameters.
