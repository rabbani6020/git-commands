## How to use Git?
### What is Git?

<p>Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.</p>

### How to collaborate in Git?

#### How to check git branch?
``` git branch ```

#### How to create new branch?
``` git branch -b branch_name ```

#### How to checkout any branch?
``` git check branch_name ```

#### How to checkout fource any branch?
``` git check branch_name -f```

#### How to delete branch locally?
``` git branch -d branch_name ```

#### delete branch remotely
```git push origin --delete remote_branch_name```

#### List all branches:
``` git branch -a ```

#### How to add all file in git?
``` git add . ```

#### How to check status my branch?
``` git status ``

#### How to add specific file in git?
``` git add file_name ```

#### How to commit?
``` git commit -m "Your commit message" ```

#### How to push?
``` git push ```

#### How to push specific branch?
``` git push origin branch_name ```

#### When work same branch how to pull later/new file or code?
````
git stash
git pull
git stash apply
````
#### How to check all commit history?
``` git log```

#### How to change local branch fetch?
``` git checkout -t origin/branch_name ```

#### How to update local branch?
````
git checkout master
git fetch
git rebase origin/master
git checkout brance_name
git rebase -i origin/master
git push origin branch_name
````

<p> Git and Bitbucket are almost same. Now I will show some consept of  bitbucket. If you work another branch how to manage I will share about that.</p>

```
git checkout master
git fetch
git checkout -b branch_name
```

##### Here, When will you finish your work/task then you follow the command
```
git add 
git commit -m "you message"
git push origin your_branch
git push origin your_branch
```

Then you will Go to bitbucket create pull request. After then check pull request(PR)

#### How to merge any branch like master?
```
git checkout master
git merge branch_name
git push origin master
```

###### Create virtualenv in your Django Project.
```virtualenv venv --python=python3.8```
