## Git :
 Versatile version contol system for tracking changes in code and collaborating with others.
 Due to a distributed version control system, Git enables you to revert to the previous state or review the project’s history.
 Git is an open-source command-line-based version-control system for software development. While Git is a command-line tool and you also need to host and maintain a server on which you can use Git for versioning.
 ## GitHub:
Popular web-hosted services for Git repositories.
GitHub is a repository hosting service that uses Git. GitHub provides a web-based hosting service with a graphical user interface(GUI) and git command line interface (CLI). It also provides access control and several collaboration features, such as wikis and basic task management tools, for every project. GitHub provides cloud storage for source code, supports all popular programming languages, and streamlines the iteration process. GitHub includes a free plan for individual developers and for hosting open-source projects.
### Git & GitHub Basic Terms :
SSH Protocol: Method to secure remote login. / A method for secure remote login from one computer to another.
<br>
Rpository: Contains Project folders. / A data structure for storing documents, including application source code. It contains the project folders that are set up for version control.
<br>
Repositories are storage structures that store documents, including application source code, and enable contributors to track and maintain version control.
<br>
Fork: Copy of a repository. / A copy of a repository into your GitHub account.
<br>
Pull Request: To request for review and approval. / A process used to request that someone review and approve your changes before they become final.
<br>
Working Directory: Contains files and subdirectories. / A directory in your file system that contains files and subdirectories on your computer that are associated with a Git repository.
<br>
Commit: Snapshot of the project's current state. / A snapshot of the project's current state at a specific point in time, along with a description of the changes made.
<br>
Branch: Separate line of development /  A separate line of development that allows to work on features or fixes independently.
<br>
Merge: Combines changes from one branch to another. / A process to combine changes from one branch to another, typically merging a feature branch into the main branch.
<br>
Clone: Local copy of the remote Git repository / A local copy of the remote Git repository on the computer.
<br>
Continuous delivery (CD):	The automated movement of software through the software development lifecycle
<br>
Continuous integration (CI):	A software development process in which developers integrate new code into the code base at least once a day.
<br>
Distributed version control system (DVCS):	A system that keeps track of changes to code, regardless of where it is stored. Multiple users work on the same codebase or repository, mirroring the codebase on their computers if needed, while the distributed version control software helps manage synchronization amongst the various codebase mirrors.
<br>
GitHub: 	A web-hosted service for the Git repository.
<br>
GitHub branches: A branch stores all files in GitHub. Branches are used to isolate changes to code. When the changes are complete, they can be merged back into the main branch.
<br>
GitLab: 	A complete DevOps platform delivered as a single application. It provides access to Git repositories, controlled by source code management.
<br>
Git: Free and open-source software distributed under the GNU General Public License. It is a distributed version control system that allows users to have a copy of their own project on their computer anywhere in the world.
<br>
Version control: A system that allows you to keep track of changes to your documents. This process allows you to recover older versions of the documents if any mistakes are made.


## Branches with GitHub
Abranch is a snapshot of your repository to which you can make change.
<br>
In the child branch, you can build, make edits, testthe changes, and then merge them with the main branch.
<br>
To ensure that changes are made by one member, do not impede or affect the workflow of other members,
multiple branches can be created and merged with the main branch.
<br>
A pull request is a way to notify other team members of the changes and edits mede to the main branch.

##  Cheat Sheet: Git Commands and Managing GitHub Projects
git add - Used to move changes from the working directory to the staging area
Code Example: git add sample.md
<br>
git add . - Allows to move the changed files into the staging area on GitHub repositories
Code Example: git add .
<br>
git am - Used to apply patches emailed to the repository
Code Example: git am < patchfile.patch
<br>
git branch - Allows to create an isolated environment within the repository to make changes
Code Example: git branch <new-branch>
<br>
git checkout - Allows to see and change existing branches
Code Example: git checkout <existing-branch>
<br>
git checkout main - Allows to switch to the main branch
Code Example: git checkout main
<br>
git clone - Allows to create a copy of the remote repository
Code Example: git clone <repository-url>
<br>
git commit - Allows you to take staged snapshots if changes and commit them to the project
Code Example: git commit -m "Your commit message here"
<br>
git config --global user.email
Example 1: Sets a global email configuration for Git
git config --global user.email "your.email@example.com"
Example 1: Sets a global email configuration for Git
git config --global user.name "Your Name"
<br>
git daemon - Used to allow anonymous download from the repository
Code Example: git daemon --reuseaddr --verbose
<br>
git diff - Helps others to review your code to identify and compare the changes
Code Example: git diff example.txt
<br>
git fetch - Used to transfer the changes from the remote repo to your local repo
Code Example: git fetch <options> <remote name> <branch name>
<br>
git fetch upstream/master - Used to grab upstream branches
Code Example: git fetch upstream master:upstream-master
<br>
git format-patch - Generates or prepares e-mail submission if you adopt Linux kernel-style public forum workflow
Code Example: git format-patch -n <number_of_commits>
<br>
git http-backend - Provides a server-side implementation of Git-over-HTTP, allowing both fetch and push services
Code Example: 
git clone --bare /path/to/repos/myrepo.git
cd myrepo.git
git update-server-info
<br>
git init - Used to clone an existing repository
Code Example:  git init <directory>
<br>
git instaweb - Allows to set up web front-end to Git repositories
Code Example: git instaweb -p 8080
<br>
git log - Enables to browse previous changes to a project
Code Example: git log -p filename
<br>
git merge - Used to merge changes in the active branch into another branch
Code Example: git merge feature_branch
<br>
git merge upstream/master - Merges changes from the 'upstream/master' branch to the current branch
Code Example: git merge upstream/master
<br>
git pull - Used to transfer the changes from the remote repo to your local repo, and merge them to a branch
Code Example: git pull origin main
<br>
git pull downstream - Pulls changes from a downstream repository, specifically from the master branch of that repository 
Code Example: git pull downstream main
<br>
git pull upstream - Pulls changes from the "upstream" repository into the current branch
Code Example: git pull upstream main
<br>
git push - 	Used to push all the committed changes into the repository
Code Example: git push origin your_branch_name
<br>
git remote - A command to manage a set of tracked repositories
Code Example: git remote add upstream https://github.com/original/repo.git
<br>
git remote add origin <URL> - Adds a remote repository named "origin" with the specified URL
Code Example: git remote add origin https://github.com/yourusername/your-repo.git
<br>
git remote add upstream - Adds the original repository as a new remote repository labeled upstream
Code Example: git remote add upstream https://github.com/original/repo.git
<br>
git remote rename - The git remote rename command is followed by the name of the remote repository(origin) you want to rename and the new name(upstream) you want to give it
Code Example: git remote rename origin new-origin
<br>
git remote -v   - 	Allows to view the remotes associated with the local repository
Code Example: git remote -v
<br>
git request-pull - 
Example 1: Creates a summary of changes for your upstream to pull
git request-pull origin/main your-branch
Example 2: Generates a summary of pending changes for an email request
git request-pull <base> <head> <repository>
<br>
git rerere - Reuses recorded resolution of previously resolved merge conflicts
Code Example: 1: git rerere  2: git rerere diff
<br>
git reset - Undoes changes that were made to the files in your working directory
Code Example: git reset HEAD~1
<br>
git revert - Used to undo botched commits
Code Example: git revert HEAD
<br>
git send-email - 
Example 1: Sends your email submission without corruption by your MUA
git send-email --to=recipient@example.com
path/to/patchfile.patch
Example 2: Sends a collection of patches as emails
git send-email --to recipient@example.com
patches/*.patch
<br>
git-shell - Used as a restricted login shell for shared central repository users
Code Example: sudo usermod -s /usr/bin/git-shell gituser
<br>
git status - Allows to see the state of your working directory and the staged snapshot of the changes
Code Example: git status
<br>
git version - Displays the current Git version installed on your system
Code Example: git --version
<br>
git web - Provides a web front-end to Git repositories 
Code Example: git instaweb --port=8080 

## Git Commands and Managing GitHub Projects
Term	Definition
Cloning -	A process of creating a copy of the project's code and its complete version history from the remote repository on the local machine.
<br>
Commit -	A snapshot of the project's current state at a specific point in time, along with a description of the changes made.
<br>
Developer - 	A computer programmer who is responsible for writing code.
<br>
Distributed version control system (DVCS) - 	A system that keeps track of changes to code, regardless of where it is stored. Multiple users work on the same codebase or repository, mirroring the codebase on their computers if needed, while the distributed version control software helps manage synchronization amongst the various codebase mirrors.
<br>
Fork - 	A copy of a repository into your GitHub account.
<br>
Forking	-  Forking creates a copy of a repository on which one can work without affecting the original repository.
<br>
GitHub	- A web-hosted service for the Git repository.
<br>
Git	-  A free and open-source software distributed under the GNU General Public License. It is a distributed version control system that allows users to have a copy of their own project on their computer anywhere in the world.
<br>
Integrator	-  A role that is responsible for managing changes made by developers.
<br>
Master branch - 	A branch that stores the deployable version of your code. The master branch is created by default and is definitive.
<br>
Merge	-  A process to combine changes from one branch to another, typically merging a feature branch into the main branch.
<br>
Origin - 	A term that refers to the repository where a copy is cloned from.
<br>
Pull request -  	A process used to request that someone review and approve your changes before they become final.
<br>
Remote repositories	-   Repositories that are stored elsewhere. They can exist on the internet, on your network, or on your local computer.
<br>
Repository administrator -  	A role that is responsible for configuring and maintaining access to the repository.
<br>
Repository	-  A data structure for storing documents, including application source code. It contains the project folders that are set up for version control.
<br>
Staging area - 	An area where commits can be formatted and reviewed before completing the commit.
<br>
Upstream -  	A term used by developers to refer to the original source where the local copy was cloned from.
<br>
Version control - 	A system that allows you to keep track of changes to your documents. This process allows you to recover older versions of the documents if any mistakes are made.