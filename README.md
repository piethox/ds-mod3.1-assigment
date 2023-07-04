# INTRODUCTION
David - Cohort 2 SCTP

This repo contains basic git commands



# Commands
## git clone
> Used for just downloading exactly what is currently on the remote repository and saving it in your machine's folder where that project is placed. **(Only one time)**

## git fetch
> Tells the local repository that there are changes available in the remote repository without bringing the changes into the local repository

## git pull
> Downloads the changes and merges them into your current branch. **(Can be multiple times if there is new changes on the branch in the repo).**

## git add .
> Add a change in the local working directory to the staging area

## git commit -m "Comment"
> Commit the file that you’ve staged in your local repository. Used to create a snapshot of the staged changes along a timeline of a Git projects history

## git push origin main
> Push the changes in your local repository to GitHub

## git status
> show modified files in working directory, staged for your next commit

## git reset
> unstage a file while retaining the changes in working directory

## git diff
> diff of what is changed but not staged

## git diff --staged
> diff of what is staged but not yet commited

## git branch
> list your branches. a * will appear next to the currently active branch
## git branch branch-name1
> To create new branch named "branch-name1"
## git checkout branch-name1
> To change working local directory to the new branch "branch-name1"
## git checkout -b branch-name2
> To create new branch named "branch-name2" and working directory to that branch