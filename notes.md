## installation
already done

## setup
*check whether your git is installed or not and its version
git --version (in terminal)

## config addition-> name, email (already done)
*list of config
git config --list

*add your username and your email id
git config --global user.name "Your Name"
git config --global user.email "Youremail@example.com"

## how git stores the changes
*git has three areas-> working directory-> current changes
*Intermediate layer-> staging

## terms
**Repository (Repo):**
A storage location for your project, including all the files and the entire history of  their changes.

**staging area**
all the tracked changes

**working directory**
all the untracked changes



## git workflow

* git init-> 
1. this generally start tracking the changes   in the code.
2. wherever you enter git init an empty git repository is created( tracker without any history is created.)

* git add your @filename
1. added to staging area(snapshot of the code is added)

* .gitignore 
1. this is the file where you can put the files and folder name which you don't want to be tracked

* git add .
1. to send all the files current snapshot to staging area

* git status
1. shows difference between staging and working directory