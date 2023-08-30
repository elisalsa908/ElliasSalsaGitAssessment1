# Part 2: Questions 
## Answer these questions in a Markdown file and link it to your README
### 1.	List three major version control for software engineering.
Local Version Control \
Central Version Control \
Distributed version Control

### 2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
Instead of a working copy, each developer gets their own local repository, complete with a full history of commits.


### 3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge

**Branch:** A version of the repository that diverges from the main working project. Branches can be a new version of a repository, experimental changes, or personal forks of a repository for users to alter and test changes.  

**Pull:** If someone has changed code on a separate branch of a project and wants it to be reviewed to add to the master branch, that someone can put in a pull request. Pull requests ask the repo maintainers to review the commits made, and then, if acceptable, merge the changes upstream.

**Push:** Updates a remote branch with the commits made to the current branch. You are literally "pushing" your changes onto the remote.

**Repository:** Git repository is a directory that stores all the files, folders, and content needed for your project, storing everything from the files themselves, to the versions of those files, commits, deletions, etc.

**Working Copy:** is a directory full of files with a . git subdirectory. It's the same as a local git repository.

**Merge:** Taking the changes from one branch and adding them into another (traditionally master) branch.

### 4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
Version Control Policy
### 5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
git log --merge. The git log --merge command helps to produce the list of commits that are causing the conflict. \
git diff. The git diff command helps to identify the differences between the states repositories or files. \
git checkout. \
git reset --mixed. \
git merge --abort. \
git reset.

### 6.	In a merged source code file, how does Git let you know there is a conflict?
The status command is in frequent use when a working with Git and during a merge it will help identify conflicted files. Passing the --merge argument to the git log command will produce a log with a list of commits that conflict between the merging branches.

### 7.	What are the steps you can take to resolve Git conflicts?
Step 1: The easiest way to resolve a conflicted file is to open it and make any necessary changes. Step 2: After editing the file, we can use the git add a command to stage the new merged content. Step 3: The final step is to create a new commit with the help of the git commit command.
### 8.	What does git revert do, and how can you use it?
The git revert command is a forward-moving undo operation that offers a safe method of undoing changes. Instead of deleting or orphaning commits in the commit history, a revert will create a new commit that inverses the changes specified. Git revert is a safer alternative to git reset in regards to losing work.
### 9.	What does git reset do, and how can you use it? 
git reset is a powerful command that is used to undo local changes to the state of a Git repo. Git reset operates on "The Three Trees of Git". These trees are the Commit History ( HEAD ), the Staging Index, and the Working Directory.
### 10.	What is the difference between git revert and git reset?
git revert as a tool for undoing committed changes, while git reset HEAD is for undoing uncommitted changes. Like git checkout , git revert has the potential to overwrite files in the working directory, so it will ask you to commit or stash changes that would be lost during the revert operation.
### 11.	True or False: It is okay to commit broken code to the main branch.
False
### 12.	True or False: A commit should only include files that are related to the change you are committing to the repo.
True
### 13.	Describe what is DevOps, how is it useful for game developers?
DevOp's principal goal is to automate and streamline, making game building more efficient and reliable. They make sure the tools and servers used by the team for game development are in good working order.
### 14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
Version Control Tool

### 15.	What is CI/CD and how can it be used to automate the game development process?CI and CD stand for continuous integration and continuous delivery/continuous deployment. In very simple terms, CI is a modern software development practice in which incremental code changes are made frequently and reliably.
