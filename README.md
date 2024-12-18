# git-master-class

## What is Version Control?

Version Control is a method of recording changes in file over time with the ability to track and manage different version of the file.  
It is also known as **_Source Control_** 

## The difference between **Git** and **GitHub**

**Git** is a version control system that allows you to track changes in your code over time and stores different version of your codes so can be 
reverted if necessary to the previous or earlier versions.

**GitHub** is a web-based platform that provide hosting for git repositories that facilitates teamwork and collaboration and issues tracking by allowing multiple developers to work on a repository simultaneously

## 3 GitHub Alternatives
* GitLab
* BitBucket
* Azure DevOps

## Difference between **_git fetch_** and **_git pull_**

**_Git fetch_** command retrieves lastest commits and other informations from the remote repository and do not merge with current local repository. We use _git fetch_ when we want to review lastest commit before merging.

**_Git pull_** does the same as _git fetch_ but merges the fetched changes to the local repository.

## **Git rebase** command

**git rebase** command allows you to move series of commits to a new commit base (branch).  
For examples, to rebase from this branch to the **main** branch, you would use:

``` Bash
git rebase main
```

## **Git cherry-pick** command

**git cherry-pick** command allows you to pick a specific commit in a branch and apply it to another branch. This is useful when you want to use a specific commit from one branch to another without merging the two branches.

``` Bash
git cherry-pick <commmit-hash>
```

``` Bash
git cherry-pick abcdef123
```

