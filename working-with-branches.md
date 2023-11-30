# Working with branches git commands.
`$ git branch`
git branch is used with the name of a new branch to create as a parameter to create a new branch.
`$ git checkout`
git checkout is used to change from one brach to an other
`$ git switch`
git switch is the same as git checkout
`$ git merge`
git merge to merge two branchegs
`$ git rebase`
git rebase to merge two branche but changing the history, rebasing is changing the base of your branch from one commit to another making it appear as if you'd created your branch from a different commit.
`$ git cherry-pick`
git cherry-pick is used to pick a specific commit and mergit to a specific branch.
## Create a New Branch:

Create a new branch and switch to it.
`git checkout -b <branch_name>`
Alternatively (Git 2.23 and later)
`git switch -c <branch_name>`
## Delete a local branch

Delete a local branch.
`git branch -d <branch_name>`
Delete a local branch forcefully
`git branch -D <branch_name>`
## Delete a remote branch

Delete a remote branch
`git push origin --delete <branch_name>`
## Rename the Current Branch:

Rename the current branch.
`git branch -m <new_branch_name>`