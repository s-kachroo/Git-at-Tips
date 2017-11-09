## How to use Git?

For Windows -> Download Git Bash ( https://git-scm.com/download/win )

For Mac     -> brew install git

For Linux   -> sudo apt-get install git

## Basic Setup on Git

1. **git --version**
   
   Lets you know your git version on your machine.
   
2. **git config --global user.name "Your Name"**
   
   **git config --global user.email "Your E-mail"**
   
   Above commands let other people who might be working on projects with you know who you are on your computer.
   

## Initialising a folder on a machine as git repository

**git init**

  Above command helps you to initialise a git repository.

## Add - Clone - Push

  **git add .**
  
  Above command command adds all the changed or untracked files to a index staging area.
  
  **git commit -m "Your commit message"**
  
  Above command command commits all changes to the local repository. 
  
  **git push origin master**
  
  Above command will push your modified code to a remote/github repository.
  
## Keeping track of file changes in repository

  **git status**
  
  Above Command will tell you about all the untracked files which have not been added to the index area.
  
  **git log**
  
  Above Command will tell you all the commits regarding the repository.
  
  **git diff**
  
  Above command shows file differences not yet staged.

  **git diff --base filename**
   
   Above command will view the changes against the base file.
   
  **git diff sourcebranch targetbranch**
   
   Above command will view changes in source branch against a target.
  
## Cloning a git repository

   **git clone URL_of_repo_which_you_want_to_clone** 
   
   Above command will clone/download the repository's code to your local machine in which you will make changes.
   
## Branching in Git Repository

   **git checkout -b Branch_Name**
   
   Above command creates a new branch and switches to it.
   
   **git checkout Branch_Name**
   
   Above command will switch your branch to New Branch.
   
   **git branch**
   
   Above command shows all the branches present in the repository.
   
   **git branch -d Branch_Name**
   
   Above command will delete the branch in local repository.
   
   **git push origin --delete Branch_Name**
   
   Above command will delete the branch in remote/github repository.

## Merging branch into another branch

   **git merge Branch_Name**
   
   Above command will merge your New Branch into the branch on which you are currently present.
   
## Fetch - Pull - Stash

   **git fetch**
   
   Above will download any changes from the remote branch, updating your repo data, but leaving your local branch unchanged.
   
   **git pull**
   
   Above command will perform a fetch and additionally merge the changes into your local branch

   **git stash**
   
   Above command will stash the changes in a dirty working repository away to the previous version.
