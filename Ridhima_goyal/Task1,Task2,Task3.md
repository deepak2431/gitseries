## Task1
Q1. What is Git and GitHub?

GIT:-

Git is a distributed version control tool that can manage a development project's source code.
Git is an Open Source Distributed Version Control System.
Git also tracks the history of changes to a
project’s source code including what specifically has been changed and who has changed what parts and when 
have they been changed, this feature is termed as Version Control.

GITHUB:-

GitHub is a cloud based platform built around the Git tool.
It allows developers to host their files in a Repository, so that others can collaborate and make suggestions on projects.
A GitHub repository can be used to store a development project.

Q2.Why is GitHub so popular?

Github is an open source platform.  It provides cloud storage for source code, supports all popular programming languages, 
and streamlines the iteration process.
Separate public and private repositories
Easy version control.

Q3. What are the other platforms similar to GitHub?
	GitLab
	BitBucket
	Source Forge
-------------------------------------------------------------------------------------------------------------------------------	

## Task - 2
Q1 How git workflow works?

Ans 1)The developers clones the central repository.
The edits which are made to the files by using commit command are stored locally and the pushed to the central repository.

Q2 What are the different stages of a git 
the project as commit, add?

Ans 2)There are 3 stages -
    Modified:
      In a repository you can maintain and write a code. When any modification are made then it can only be 
      done on the remote repository, that simply means changes in the code can be done without changing the original code.
   Staged:
      It comes before the actual implementation of changes.The new files are pushed to the staging area and 
      then joined to the remote repository.
   Commit:
      Commit is a set of new files added to the project as a part of modification to the remote repository.

Q3 Is it possible to a git commit before git add. if you have made any changes? Explain why?

Ans 3)It is not possible to do a git commit before git add.

Q4 Why is git diff used?

Ans 4)This command is used to check the difference between the files in the stage and in the workspace.

Q5 Can we leave the commit message as blank?

Ans 5)Yes we can do it by using the below command :
git commit -a --allow-empty-message -m "message"

-----------------------------------------------------------------------------------------------------------------------------
## Task3

Q1) What is meant by the term fork and clone?

Fork in git means making a personal copy of others repository which we can modify
without affecting the orignal project.

Clone is used to create  a local copy of the remote repository.This process helps us to edit and modify files locally.

Q2) What are branches in Github?

A Git Branch is a separate line of development in a software project. 
User can create a branch, and keep on committing their changes to this branch without messing the original 'master' branch.

Usually, each developer working on a code makes his/her changes in a separate branch.
Git offers features to merge the branch with the master branch after changes are done. 
The branches can also be named according to what kind of changes they contain. 

Q3) What is PR ?

A pull request is submitted when you’ve worked on some code from a particular branch and want to inform 
the others of the changes you’ve made. people can be assigned to review and subsequently approve the request 
before your changes can be incorporated into the branch.

Q4) Can we delete the master branch if not why?

Yes, we can delete the master branch if we set some another branch as default.

Q5) How can we delete a branch?

It can be done by using git branch -d command.

Regards, 
Ridhima Goyal
