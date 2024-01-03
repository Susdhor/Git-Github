# Git-Github
All Git & Github necessary documents and cheat Sheet
<br>
Author -- Sushanta Dhar
# Defination of Git: 
Git is a distributed version control system (VCS) used for tracking changes in source code during software development. It allows multiple developers to collaborate on projects, keeping track of their contributions, and provides a history of changes made to the codebase.Git is like a super-smart tool that helps you keep track of all the changes made to the code.
Initialize a Repository:

Command: git init
Example: git init (This initializes a new Git repository in the current directory.)
Clone a Repository:

Command: git clone <repository_url>
Example: git clone https://github.com/example/repo.git (This clones a repository from a URL to your local machine.)
Check Status:

Command: git status
Example: git status (This shows the status of changes as untracked, modified, or staged.)
Add Changes:

Command: git add <file>
Example: git add filename.txt (This stages changes in the file for the next commit.)
Commit Changes:

Command: git commit -m "Your commit message"
Example: git commit -m "Added new feature" (This saves the changes with a descriptive message.)
View Commit History:

Command: git log
Example: git log (This shows a log of all commits with commit messages, authors, and timestamps.)
Create a Branch:

Command: git branch <branch_name>
Example: git branch feature-branch (This creates a new branch for a new feature.)
Switch Branch:

Command: git checkout <branch_name>
Example: git checkout feature-branch (This switches to the specified branch.)
Merge Branches:

Command: git merge <branch_name>
Example: git merge feature-branch (This merges changes from one branch into another.)
Pull Changes from a Remote Repository:

Command: git pull origin <branch_name>
Example: git pull origin main (This fetches changes from the remote repository and merges them into the current branch.)
Push Changes to a Remote Repository:

Command: git push origin <branch_name>
Example: git push origin main (This pushes changes to the remote repository.)
Discard Changes in Working Directory:

Command: git checkout -- <file>
Example: git checkout -- filename.txt (This discards changes in the working directory for a specific file.)