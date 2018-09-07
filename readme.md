# Feature Branch Workflow

## Team
Gowri Datta, Roy Lin, Nicholas Rocchi, Mihika Sharma, Chloe Bercy

## The Basic Git Workflow
The Basic Git Worklow is characterized by the process of simply adding new features and code directly to the master branch.

## The Feature Branch Git Workflow
The Feature Branch Workflow is characterized by the process of creating new branches to add new features, and merging them once they are all set and done.

## Key Differences
The _Feature Branch Workflow_ allows you to work on new features without the danger of breaking the current working master branch, which may have already been released. The _Basic Workflow_ works from the master branch, so there is a higher chance of the developer interfering with the current working model.

## Link to Clone Repo
[Here is the link to clone this github repository](https://github.com/Roylinty/GitWorkFlowRL.git)

## Diagram of workflow
This is a general idea of how it works:

master  -->  master  -->  master  -->  master(with feature-branch)

\\_ feature-branch --> feature-branch _/

## Process

### Clone the repo.
Use the command `git clone https://github.com/Roylinty/GitWorkFlowRL.git`.

### Start with master.
Use these commands:
```
git checkout master
git fetch origin 
git reset --hard origin/master
```

### Create a new branch. 
Use the command `git branch gowridatta-feature-branch`.

### Switch to the branch you created.
Use the command `git checkout gowridatta-feature-branch`.

### Create the file
Create a file with some text in it

### Add to staging area
Use the command `git add -A` to add all changes made.

### Commit changes
Use the command `git commit -m "Your descriptive sentence"`.

### Push to github
Use the command `git push -u origin gowridatta-feature-branch`.

### Submit a pull request.
And merge!


###### Written by Gowri Datta
