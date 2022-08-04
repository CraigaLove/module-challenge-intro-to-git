## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? Git is a version control system to keep track of your history and how it's changed overtime.

2. What is the difference between Git and GitHub? Git is the version control system, Github is the cloud based storage where you manage your code
3. Why do we create a branch? git checkout -b "branch-name"
4. What is the purpose of a Pull Request? The purpose of a pull request is for your work to be checked before being merged with the main branch of code. 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main. git checkout main  
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? git fetch is used to download contents from a remote repository. git merge puts forked history back together, integrates the lines of dev into the main branch. git pull is used to update local version of the repositroy from remote, updates the current local working branch and remote tracking branches. 
7. What is a merge conflict? A merge conflict is when two different branches have made edits to the same line in a file, or if one was deleted in one branch but edited in another. 
8. How do you resolve a merge conflict? In git, run git status to see which files have a conflict based on the conflict markers, decide what you want to keep and make the appropriate changes and then remove the conflict markers. 
