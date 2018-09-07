(tried my best and used logical guessing, idk if it is 100% right)

Team Names:  Gowri Datta, Roy Lin, Nicholas Rocchi, Mihika Sharma, Chloe Bercy

Name of Workflow:  Feature Branch Workflow

Description of Basic Git workflow:
  - only one branch
  - all edits/changes made on that one branch

Description of Feature Branch workflow: 
  - creates branches from the master to develop "features" or edit code
  -merges feature branches back to the master when the change is ready

Key Differences from basic workflow, and key use cases
 - allows multiple people to work (create new features) without messing up main codebase
 - allows others to comment/give feedback on work before integrating it into the main code

Link to your Git example repository: ???

Diagram or Diagrams of workflow:

feature 1:                   --◌---◌-----
(create feature branch)  -> /           | 
master:        ●-----------●------------●--------●------●-●-●
                                         \      / <-- (merged back into master)  
feature 2:                                --◌-◌-


Documentation of git commands used, and sample sequence of commands used in creating your repository

#start on master branch
git checkout master  
#get latest changes from the repository
git pull origin master
#create feature branch
git checkout -b chloe-branch
#check (just for fun): should be "nothing to commit, working directory clean"
git status
#modify the code/something
git commit
#push branch to a remote repository (named origin)
git push origin chloe-branch
#create a pull request -- if this was a "Feature Branch and Merge requests" workflow
