#Test file only
Looking for git in: /usr/local/bin/git
Using git 2.30.0 from /usr/local/bin/git
> git rev-parse --git-dir
Open repository: /Users/luongminhcong/GitHub/micmeoad
> git status -z -u
> git symbolic-ref --short HEAD
> git rev-parse master
fatal: ambiguous argument 'master': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
> git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname)
> git remote --verbose
> git config --get commit.template
> git config --local branch.master.github-pr-owner-number
> git show --textconv :README.md
> git ls-files --stage -- /Users/luongminhcong/GitHub/micmeoad/README.md
> git check-ignore -v -z --stdin
> git status -z -u
> git symbolic-ref --short HEAD
> git rev-parse master
fatal: ambiguous argument 'master': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
> git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname)
> git remote --verbose
> git config --get commit.template
> git status -z -u
> git symbolic-ref --short HEAD
> git rev-parse master
fatal: ambiguous argument 'master': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
> git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname)
> git remote --verbose
> git config --get commit.template
> git add -A -- .
> git -c user.useConfigOnly=true commit --quiet --allow-empty-message --file -
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: no email was given and auto-detection is disabled
> git config --get-all user.name
> git status -z -u
> git symbolic-ref --short HEAD
> git rev-parse master
fatal: ambiguous argument 'master': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
> git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname)
> git remote --verbose
> git config --get commit.template
> git status -z -u
> git symbolic-ref --short HEAD
> git rev-parse master
fatal: ambiguous argument 'master': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
> git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname)
> git remote --verbose
> git config --get commit.template
