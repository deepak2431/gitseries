#**Task 2**
My name is `Yashika mittal`. Pursuing my bachelors in CS from `DIT University`.
Here is my github repo link: *https://github.com/yashika0998/git-learning*

##Q1 ) How a git workflow works ?

Workflow are these 4 :  Workspace   Index -  local repository - remote repository.
Firstly clone repo if not done yet. If we have a file in our workspace , three can be 3 possibe states :

1.	Committed – which means latest changes in our data Is safely stored in local repository .
2.	Modified – means changes done in data will not be reflected in local repository.
3.	Staged – means file is the part of index, i.e. to be considered in next commit.

##Q2 ) What are different stages of a git project as  commit,add?

1.	To get access to the repository : git command followed by URL . Ex : `git (http://......)`
2.	To add a file in workspace to index : add command is used , which is not yet committed.
3.	So, to commit all the changes in local repo : commit –a  command is used.
4.	Push will allow the changes to be visible to the other users.
5.	To get changes directly to workspace we pull it. It work as (fetch+merge).

##Q3 ) Is it possible to do a git commit before git add. If you have made any changes? Explain why?

	It is not possible to do a git commit before git add. Commits can be made on added data only. All the changes in working directory and then save the changes to the repo through commit command.

##Q4) Why is git diff used?

This command is used to check the difference between the files in the stage and in the workspace.

##Q5). Can we leave the commit message as blank?

Yes we can do it by using the below command :
git commit -a --allow-empty-message -m ""

#**Task 3**
##Q1. What is meant by the term fork and clone?
Fork of repository means  we create a copy of the original repository (upstream repository) but the repository remains on our GitHub account. Whereas, when we clone a repository, the repository is copied on to our local machine with the help of Git. It can be clones on any folder we want.

##Q2. What are branches in Github?
A branch is an individual project pr files inside a repository. The default branch is the Master branch. Once we have made changes in the file we can merge that branch to the master branch. All the branches are independent to each other. We can made new branches in master branch .
##Q3. What is PR?
PR stands for Pull Request. User issues a pull request if he has forked and cloned someone’s else code and modified it and want to publish that code on the author’s repository. Then a pull request is issued.  The one who has created the repository can review and then approve the request to incorporate the changes that has been created.
##Q4. Can we delete the master branch if not Why?
Yes
##Q5. How can we delete a branch? 
NO we cant delete Master branch as soon as we use command " git init", Master branch gets activated by default.

