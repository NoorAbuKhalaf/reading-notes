## Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes
## Local Version Control
A Local VCS entails one database on your hard disk that stores changes to files.
**_So, what is Git?_**
Snapshots, Local Operations, Tracking Changes, Loss of Data, States 
## History of GIT
Git traces its roots to the open source software project Linux kernel. Developers of this project began 
using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s
## Download Git
1. Mac OS X : Terminal, Git Website, GitHub
2. Windows: Git Website, GitHub

## Setting up a Git Repository
1. Importing: To import an existing project or directory into Git, follow these steps using the Terminal or Command Line: Switch to the target project’s directory , Use the git init command , To start tracking these repository files, perform an initial commit by typing some commands.
2. Cloning : You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL 

## Local Repository Structure
1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

## Saving changes 
All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

## The Life Cycle of File Status
1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage the modified file.
3. you commit staged changes.

## how Check File Status
To determine the state of files, utilize the git status command:

## Tracking and Staging a New File
1. Single File : Track one file only by using the following format : git add filename
2. All Files : $ git add *

## Committing a File
After staging one or multiple files, you should commit the changes and record what you did within the commit message: $ git commit -m “made change x,y,z”
