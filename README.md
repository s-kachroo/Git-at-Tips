# Git-at-Tips

This repository is having the basic commands related to Git which a individual needs to know.


# How to use Git?

For Windows -> Download Git Bash ( https://git-scm.com/download/win )

For Mac     -> brew install git

For Linux   -> sudo apt-get install git

# Basic Commands on Git

1. **git --version**
   
   Lets you know your git version on your machine.
   
2. **git config --global user.name "Your Name"**
   
   **git config --global user.email "Your E-mail"**
   
   Above commands let other people who might be working on projects with you know who you are on your computer.
   

# Initialising a folder on a machine as git repository

**git init**

  Above command helps you to initialise a git repository.

# Add - Clone - Push

  **git add .**
  
  Above command command adds all the changed or untracked files to a index staging area.
  
  **git commit -m "Your commit message"**
  
  Above command command commits all changes to the local repository. 
  
  **git push origin master**
  
  Above command will push your modified code to a remote/github repository.
  
# Keeping track of added and commited files in repo

  **git status**
  
  Above Command will tell you about all the untracked files which have not been added to the index area.
  
  **git log**
  
  Above Command will tell you all the commits regarding the repository.
  
# Cloning a git repository

   **git clone URL_of_repo_which_you_want_to_clone **
   
   Above command will clone/download the repository's code to your local machine in which you will make changes.
   
# Branching in Git Repository

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
