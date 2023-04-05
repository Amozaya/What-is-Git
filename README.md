# GitHub and version control

## What is Git?
Git is one of the most popular version control systems (VCS). It is free, open source, and provides version history.
Git comes with a command-line user interface (CLI) called Git Bash.


## What is GitHub?
GitHub is a cloud-based service that allows developers to store and manage their code, as well as track and control changes to their code. 
As a cloud based server it makes it much easier for developers to collaborate together and share their code.

It allows users to create remote repositories, that can be copied to the device, modified and then pushed back to the repository with all the changes made.

## What is the difference between the two?
Git is local, meaning your repository is saved on your machine, and all the changes you do to your code will be saved localy as well, when GitHub is based on the cloud server.

When you make any changes to your code in your "Working Directory", first you need to use git commands to create a snapshot of your code and add it to the "Staging area".

Once snapshots of code are done, you can commit your code and it will move all of the snapshots from the staging area to the local repository, storing them and creating a new version. When you commit, it is important to add a clear comment about what changes were made in that version, so if you need to go back to the previous version it will be much easier to do so.

At this stage, you can push your commits from your local repository to cloud-based repository in GitHub to make it accessible for other to view and make changes.

## The main benefit of having version control is:
* Allow to keep track of all the documents and all the version
* Easy synchronization with a local copy
* Support collaboration, as anyone can work on anything

## Main Git commands
* git init - creates a new local repository in the current folder
* git add - adds files to stage area. You can add just specific files using "git add <filename>", or add all the files in the folder "git add ."
* git commit - commits changes, moving all the code snapshots from staging area to local repository. You should also add a clear message about the changes in current commit following this example "git commit -m "Commit message""
* git push - sends all the changes to remote repository, such as GitHub 
* git branch - allows to create a new branch, meaning if you want to work on some experimental code without affecting the main code, you can create a new branch and then later decide if you want to merge the changes or just switch back to the original version
* git merge - allows you to merge different branch into your main branch
* git pull - fetches and merges the files from remote repository to your local one
