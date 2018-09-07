# FeatureBranch Workflow
## Team members 
Roy Lin, Gowri Datta, Mihika Sharma, Chloe Bercy, Nicholas Rocchi

## Description of Basic
Basic is where there is a central repository, and each person is able to add their own changes via commits and allows other people to use their code.

## Description of Featurebranch
Featurebranch is where a single project has multiple projects, so people can add different feautres on a separate branch, and when the project is ready, they can all be merged so that no conflicts will occur.

## Key Differences from Basic
Featurebranch uses branches instead of the master branch, and its advantage is that when a person needs to modify something, they can do it without having to meddling the master branch.

## Diagram
master --> master -->  master --> master (feature branch included) 
           
............^-- feature ---> feature(merge) --^

## How to start

## Beginning

In git bash, use:
`git checkout master`

`git fetch origin`

`git reset --hard origin/master`

This switches the repo to the master branch, pulls the latest commits and resets the repo's local copy of master to match the latest version.

## Create a new-branch

Type `git checkout -b new-feature`

This checks out a branch called new-feature based on master, and the -b flag tells Git to create the branch if it doesn’t already exist.

## Update, add, commit, and push changes

Do your changes, and when you're done, type:

`git status`

`git add <your-file>`

`git commit`

Do this whenever you change your files!

## Push feature branch to remote

Once committed, type:

`git push -u origin new-feature`

This command pushes new-feature to the central repository (origin), and the -u flag adds it as a remote tracking branch. After setting up the tracking branch, git push can be invoked without any parameters to automatically push the new-feature branch to the central repository. 
