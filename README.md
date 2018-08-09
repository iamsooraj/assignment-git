# Basic Git Commands

## init Command

init command converts a local directory into a Git repository.

`$ git init`

## clone Command

clone command is used to clone a remote repository to local machine.

`$ git clone <remote repository url>`

## status Command

status command checks the status of your files in your repo.

`$ git status`

## add Command

add command has multiple purposes. It tracks new files and also Stage modified files before committing.

`$ git add <file name>`
or
`$ git add .`-> to add all files and folders in the repo.

## commit Command

commit command permanently saves your changes.

`$ git commit -m "<commit message>"`

## rm Command

rm command removes file from your tracked files and then commit.

`$ git rm --cached <file_name>`

## log Command

log command will show the history of commits.

`$ git log`
`$ git log n`--> show difference introduced in each commit
`$ git log --pretty=oneline`--> show log in one line

## amend Command

ammend command redo the last commit

`$ git commit --amend`

## checkout Command

checkout command moved the head to a specified commit state or branch

`$ git checkout <checkout point>`

## push Command

push command is to push files to the remote repository

`$ git push -u <remote> <branch>`

## branch Command

branch command is used for creating and managing branches in a project

`$ git branch`--> list all branches
`$ git branch <newBranchName>`

## merge Command

merge command merges 2 branches together

`$ git merge <branch2>`--> from branch1 will merge branch1 and branch2

