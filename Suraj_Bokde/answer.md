Task 1 Solution-
What is Git and github?
 --Git is an open-source distributed version control system that keeps track of software assets and helps run more efficient development processes.
In a distributed version control system (DVCS), the version information is maintained with every copy of the code.
 It allows peer-to-peer sharing. 
Git is simple nd powerful with the following pros:
Performance:. Commits, branching and merging is faster in Git than centralized version control systems like CVS, SVN.
Security:The integrity of the code is easier to verify on Git. It uses SHA1 cryptographically secure hashing. The hashes are unique to each modification. If anyone changes a modification, the hashes will not match.
 This property of Git makes it harder for anyone to sneak in code changes surreptitiously.
Flexibility: Git was designed to adapt to any workflow. Older version control systems are more restrictive. 
But Git gives your team more leeway. You can even create a centralized workflow or integrate with other version control systems to make your legacy systems work. 

--Github -it is the website that hosts Git repositories online, making it easier for developers to share code.
GitHub makes it easy to share code between multiple computers and developers. It's become the centralized organization tool of the open source community and, in turn, is used by thousands of companies and teams. 
Some GitHub users have one repo they work with every day, some have hundreds.

Task 2-

--How git workflow works?
Git works on four fundamental elements 
1.Workspace-working directory
2.Index(stage)-project is added and ready to be commited
3.Local Repository-it resides in our systems and contains all the files with their commit history
4.Remote Repository-repository on the server to which every member will have access

--What are the different stages of git project as commit,add?
different stages of git project are modified,staged and commit.
1.modified-we can make changes to copy of our project without hampering the orignal code
2.staged-the files which are added and ready to be commited but not yet commited 
3.commit-the staged files are commited to local repository

--Is it possible to do a git commit before git add?if no,explain why?
 No,It is not possible because as per git workflow first we have to add file from 
working directory to local index and then it can be commited. 

--why is git diff is used?
git diff is used to track the changes made in the project.
It compares the commited file with the file in staged area.

--Can we leave the commit messages as blank?
Yes,it can be done by using  ( git commit -a --allow-empty-message -m "")