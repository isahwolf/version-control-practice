# version-control-practice
* Practice repo for Version Control - D197

## Basic commands
* `git status` provides info on the current state of your git repo
* `git add` adds changes to the staging area
    * `git add .` adds all changes
    * `git add example.md` would only add changes from `example.md`
* `git commit -m "message"` records the changes in the staging area
* `git push` uploads the local repo content to the remote repo
* `git log` shows the commit history
* `git diff` shows the changes between various states of your repo
* `git checkout` to revert to older version

## Process to push changes
1. `git status`
2. `git add .` or `git add 'filename'`
3. `git commit -m "message"`
4. `git push`