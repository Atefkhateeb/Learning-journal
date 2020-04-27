# Summary 

**Version Control** is a system that allows you to revisit various versions of a file or set of files by recording changes. 

Features of Version control: 
1. track modifications 
2. modifying individuals and compare changes
3. mistakes with files can easily be rectified.

What is the differance between centeralized and distributed version control? 
![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190820174942/CVCS-vs-DVCS.png)

**Git** DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

To import an existing project or directory into Git, follow these steps:
- Switch to the target project’s directory
- Use the git init command
- To start tracking these repository files, perform an initial commit by typing the following
  -$ git add *.c
  -$ git add LICENSE
  $ git commit -m “any message here”
**You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:**
*$ git clone https://github.com/test*

**To determine the state of files, utilize the git status command**
**Track one file only by using the following format**
*git add filename*
**After staging one or multiple files, you should commit the changes and record what you did within the commit message**
**Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.**

