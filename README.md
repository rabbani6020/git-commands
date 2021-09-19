# git-commands

How to collaborate in git
===================
git checkout master
At first latest update code using (git fetch)
git rebase origin/master
Create branch (git checkout -b branch-name)
When work done push branch (git push origin branch-name)
Go to bitbucket create pull request
Check PR
Force push git (git push origin branch_name -f)

How to update local branch:
git checkout master
git fetch
git rebase origin/master
git log
git checkout brance_name
git rebase -i origin/master
git push origin branch-name

List all your branches:
git branch -a
Confirm you are now working on that branch:
git branch
git reset HEAD~1 (rest commit)

How to create branch:
git checkout -b `your_branch_name`


How to change local branch fetch:
git checkout -t origin/branch_name
