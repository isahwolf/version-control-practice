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
    * q closes the log
* `git diff` shows the changes between various states of your repo
* `git mv` renames a file
* `git revert` to revert to older version
* `git restore` will undo changes in the working directory or staging area
* `git checkout` will restore file to last commit
* `git checkout -b <new-branch-name>` will create a new branch
* `git tag` or `git tag -a` to create tags
    * `git tag --list` or `git tag -l` to view tags
    * `git tag --delete` or `git tag -d` to delete tags locally
    * `git push origin :v1.11` would delete tag v1.11 from the remote server
    * `git push origin v1.11` to push tag v1.11
    * `git push --tags` to push all tags

## Process to push changes
1. `git status`
2. `git add .` or `git add 'filename'`
3. `git commit -m "message"`
4. `git push`

## Tags
* Named reference to a commit
* Often used to mark releases
* There are two tags that you can create
    * Lightweight tag
        * Ex: `git tag issue136 655da716e7`
    * Annotated tag (most common)
        * Ex: `git tag -a v1.1 -m "Version 1.0" dd5c49428a0`