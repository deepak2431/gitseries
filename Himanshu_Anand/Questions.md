##########    DAY 1 QUESTIONS AND ANSWERS ######
1> What are Git and GitHub?
Git is a tool that is used to store different versions of a file in a remote or local repository. It is used to store different versions of a file in a remote or local repository. It is used to track changes in the source code. 
GitHub is a remote repository present on the web which lets you store your files on the web. It gives an opportunity to contribute in any projects worldwide. We can interact with GitHub using a command-line interface tool called Git.

2> Why GitHub is so popular and used in most of the projects?
GitHub is the world's largest software development platform. It provides cloud storage for source code and supports all popular programming languages. Navigating through source files is always very fast.  It also provides access control and several collaboration features, like basic task management tools for every project. It is one of the largest coding communities around, so using it can provide wide exposure for your project.

3> What are the other platforms similar to GitHub?
•	Bitbucket
•	GitLab
•	SourceForge
•	Cloud Source Repositories by Google
•	AWS CodeCommit. 





##########    DAY 2 QUESTIONS AND ANSWERS ######

1> How git workflow works?
The git workflow has 4 parts: Workspace, Index, Local repository and Remote repository.
Workspace: A workspace is simply a set of git repositories.
Index: The Git index is used as a staging area between your working directory and your repository. 
Local Repository: A Git local repository is the one on which we will make local changes, typically this local repository is on our computer.
Remote Repository: A remote in Git is a common repository that all team members use to exchange their changes. 

2> What are the different stages of git project?
Different stages of a git project:
1. Modified : making some additions to the original project.
2. Staged:  all the new files are finally ready to be joined to the remote repository. the staged files are ready to be committed.
3. Committed: successfully applied a certain modification to the code.

Is it possible to do a git commit before git add? If No, explain why?
No, it is not possible to do a git commit before a git add.
We have to add files to the staging area and only then we can commit to make the changes permanent.

3> Why is git diff used?
Diff command is used in git to track the difference between the changes made on a file. Diff command takes two inputs and reflects the differences between them.

4> Can we leave the commit messages as blank?
Yes, we can leave the commit messages as blank by using the following command:
git commit-a —allow-empty-message-m “ “

My GitHub repository link:
https://github.com/himanshu295/Git_Learning_Series





##########    DAY 3 QUESTIONS AND ANSWERS ######

Ques1: What is meant by the term fork and clone?
Ans: Fork: it is basically the copy of the repo i.e. you can do the experiments or modifications in the project without harming the actual one. though we can pull the change in the orig repo by pulling it.Clone: cloning the repo is basically making copy of remote repo in the form of local repo. 

Ques 2: What are branches in Github?
Ans: Branch is basically a part or version of repo. a single repo can have multiple branches and multiple branches can be merged into one as well. By defeault : Master branch.e.g. if we are working on project under master branch and suddenly we create another branch names X and continue the project, we can go back to that instance where we created branch Xi.e. working on branch will not affect other branches thus helping in creating and accessing the different versions of the projects. 

Ques 3. What is PR?
Ans: PR: PULL REQUEST. It let you tell others about changes you've pushed to a branch in a repository on GitHub. 

Ques 4.Can we delete the master branch if not Why?
Ans: NO we cant delete Master branch as soon as we use command " git init", Master branch gets activated by default. 

Ques 5. How can we delete a branch? 
Ans: use command : git branch -d <name of the branch

PR links:
https://github.com/deepak2431/gitseries/pull/28
https://github.com/deepak2431/gitseries/pull/30
