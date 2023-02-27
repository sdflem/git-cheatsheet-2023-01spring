# Git Cheatsheet

`git init`
Make the current directory a Git working tree and add an empty Git repository to the directory.

`git status`
Check the status of the working tree.

`git add -A`
Stage all changes present in the working tree.

`git commit -m "Log message goes here"`
Save all staged changes to the local repository as a new commit.

`git log`
Basic command for inspecting the version history. Hit the Q key to quit.

`gloga`
`git log --oneline --decorate --graph --all`
A version of the `git log` command which displays the version history as a graph. Hit the Q key to quit.

`git checkout <COMMIT_HASH>`
Change the working tree to contain the version of the code saved in a older commit.

`git switch <branch-name>`
Switch to the specified branch.
