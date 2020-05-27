Day 1 task:
Good morning everyone, my name is Arup Maji . I am currently pursuing my b-tech degree on ECE dept from ASANSOL ENGINEERING COLLEGE.

Q)What are git and GitHub?
--> Git refers to a distribution version control system that lets us manage and keep track of our source code history.
GitHub is a cloud based hosting services that lets us manage git repositories.
It is like a database where we can save different versions systematically and can be accessed easily. It is a server where we can save the remote repositories

Q)Why GitHub is so popular and used in most of the projects?
--> There are many such platform other than Github but we preferably use Github due to following reasons--
i) It gives collaboration with security and administrative features built for teams.
ii) Management of Chaos is damn easy .
ii) Very easy to find right tools and to implement them.

Q)What are the other platforms similar to GitHub?
--> Other platforms are --
i)   BitBucket
ii)  AWS CodeCommit
iii) SourceForge
iv) Launchpad
v)  Phabricator



Day 2 task:

Good morning everyone, my name is Arup Maji from asansol engineering college.


 a. How git workflow works?
-->  First we create a file and save it.
Then we go to git bash and add that file as newly added. Then we commit it so that it is saved in the local repositories so that we can use it as a checkpoint in future. Then we can upload that file to remote repository of github (or any other platforms) where the files are accessed globally by everyone.
More precisely--
i) workspace
ii) index stage
iii) local repositories
iv) remote repositories


 b. What're the different stages of a git project as commit, add? 
--> In commit we save the file in local repository. But in add we just add the file and say gitbash that we are keeping this file for committing (but it is not yet committed).


c. Is it possible to do a git commit before git add . if you have made any changes? Explain why?
--> No it is not possible. First we have bring the file to the stage area which is only possible through add.



d. Why is git diff used?
-->  This command is used to find the difference between the last saved commit ( or last file in stage area) amd the recently working file or directory.



e. Can we leave the commit message as blank?
--> Yes we can leave the commit message as blank .

 By using the command :
git commit -a --allow-empty -message -m ""

Day 3 task:

Hello everyone, i am Arup Maji from Asansol engineering college. 
**************
Task 3 :


a. What is meant by the term fork and clone?
--> Fork is used when we want to make changes to someone's file in repository. It is very much useful in managing bugs as well as when we like to work on someone else's project.

Clone is used after we successfully forked someone's repository and now we are ready to work on the forked project. It is generally used to make the copy of the main file and get that file to the local sever so that we can work on it.




b. What are branches in Github?
--> Branches is a very vital concept in Github's world. When we are working on a project we generally work on master branch (default). But when we need to do some experiments or more simply when we want to make changes to our project which we are not sure to add them to the existing master branches, then comes the branching. One very great advantage of branching is that later on if we do some changes and if we want to add that file to master branch, we are always welcome for that. 




c. What is PR?
--> PR refers to pull request. When we successfully forked someone's repository and cloned it to the local machine and made the desired changes, then if now we wanted to do that changes in the actual repository we need a pull request. In simple words pull request may be considered as we are requesting the actual developer of the code to go through our edited code and pull the code if he finds it necessary.




d. Can we delete the master branch if not Why?
-->  Yes we can delete it. But we have to change the default branch to some else branch (other than master branch).




e. How can we delete a branch?
-->  To delete the branch locally, we need command ---
git branch -d <branch>
To delete the branch in github --

On GitHub, navigate to the main page of the repository.

•Above the list of files, click  NUMBER branches.

•Scroll to the branch that you want to delete, then click delete.

PR link 1 :   https://github.com/deepak2431/gitseries

PR link 2: https://github.com/arupmaji404/hello_git/compare/master...alpha
