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
  
# Keeping track of added and commited files in a git repository

  **git status**
  Above Command will tell you about all the untracked files which have not been added to the index area.
  
  **git log**
  Above Command will tell you all the commits regarding the repository.
