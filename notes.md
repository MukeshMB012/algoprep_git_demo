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

* git commit -m "commit message"
1. A snapshot of changes made to the repository. Each commit has a unique ID and a message describing the changes.

* git log
1. list of commits with user name, email address, date, time will appears.
2. type q in case you won't find               PS C:\Users\Mukesh\Desktop\Git_demo>

* git checkout commit-hash(paste the commit hash you get from git log)
1. you can view how code looked like in a particular commit
2. it will get you back to the situation of the code from where you picked the commit hash.

* git branch
1. list of branches will came
2. select the branch
3. type the git checkout + branch name you selected
4. it will lend you to the code of that branch(or say the code of that timeline)
in short-->
to go back to latest commit -> 'HEAD'
type git branch -> check your branch name
git checkout branch-name


## Commands to push your changes
**Setup remote repo**
* create a repo in github
* git remote add origin 'remote-repo-name'
* git branch -M main
<!-- usuall drill -->
* git push -u origin main
<!-- do all three steps when you create repo for the first time. -->
<!-- only apply 3rd step when the repo is already formed and you did the little changes in the codes -->
