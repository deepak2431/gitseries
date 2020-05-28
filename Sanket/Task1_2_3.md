#TASK 1

#1.What are git and GitHub?
Git is distributed version control system.It is used to commit or save different versions of project with better understandable version names and its features.Git is program installed in system. Git comes with advantage of local repository .GitHub is website which provide repository to store different versions of project.Github allow us to create remote repository on website.


#2.Why GitHub is so popular and used in most of the projects?
We can stire our all projects at one place
Acess anytime anywhere
Separate public and private repositories
Easy to contribute in project and easy for team work

#3.What are the other platforms similar to GitHub?
Amazon code commit
GitBucket
Source Forge
Cloude source repositories

_______________________________________________________________

#TASK 2

Hello Everyone
I am Sanket Latkar,pursuing B.E. in I.T. from Yeshwantrao Chavan College of Engineering , Nagpur.

#A. How git workflow works?
#B. What're the different stages of a git project as commit, add? 
Ans : 
Git workflow includes 4 stages ,that are:
1)Workspace(Working Directory)
2)Index(Stage)
3)Local Repository(Head)
4)Remote Repository

Workflow for pushing file to remote repo is :
Clone command creates a local copy of the repository in working directory.
Add command adds the file from working directory to the Index.
Then after commit, file get saved in local repo.
By using commit -a ,we can combinely do the work of add and commit.
After this by using Push command,we pushes file from local repo to remote repo.Once file get pushed in remote repo it can be viewed to all if its public repo and to specific authority if its private repo.

Workflow to fetch files from remote repo is:
Fetch : Fetch command is used to fetch file from remote repo to local repo.
Merge : Merge command is used to fetch file from local repo to working directory.
Pull : Pull command help us to fetch file directly from remote repo to working directory.


#C. Is it possible to do a git commit before git add . if you have made any changes? Explain why? 
Ans. No,It is not possible to a git commit before git add . Because as per git workflow first we have to add file from working directory to index and then commit it into local repo.

#D. Why is git diff used?
Ans. git diff is used to know difference between status of files in repo after changes. git status is used along with git diff for analyzing file status more clearly.

#E. Can we leave the commit message as blank?
Ans. Yes ,we can use the commit message as blank.Because git provide facility as commit message for more understanding of each commit,Otherwise we can choose not to use this facility and keel commit message as blank.

Github repo. link : 
https://github.com/SanLatkar/Restart 

________________________________________________________________

#TASK 3

#Q. What is meant by the term fork and clone?
Ans.: Fork is personal copy of someone else's projects.Fork acts as a sort of bridge between the original repository and iur personal copy.We can pull request to make contribution in other's project.But its solely depends on will of original programmer whether to make that changes or not.Still if for someone other if our changes are useful they can use it.
Clone means to copy our own repository to local computer to modify it.

#Q.What are branches in github?
Ans.: A branch is an independent project link.Default branch is master,but we can change default branch. If we found two independent branches have compatible changes then it is useful to merge them.We can add as many branches we want and each one can be independent of each other.

#Q.What is PR?
Ans.:PR or pull request are made to the owner of a forked repo so that he can see the changes done in the repo and based on that ,can approve the changes or not. If he approves the changes will be made to author's repo as well.

#Q.Can we delete the master branch if not why? 
Ans.: We can delete master branch but before that we have to assign default branch status to some other branch.

#Q How can we delete a branch?
Ans.: git branch -d command is used to delete a branch.

_________________________________________________________________