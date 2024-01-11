# git-github-notes
Notes for git amd github

# Developers will not store code in local system, instead move the code in remote server

# What is Git?
- Use for code changes, who make code changes, and coding collaborations.
- Git is a popular version control system (VCS), created by Linus Torvalds and been maintained by Junio Hamano.

# Git Branching Strategy
- ###### Development Branch
- ###### Main Branch
- ###### Release Branch
- ###### Hotfix Branch
- ###### Fork Branch

# Git command operations
- ###### git fetch
- ###### git rm
- ###### git stash
- ###### git diff
- ###### git revert
- ###### git mv 
- ###### git show
- ###### git rebase
- ###### git help
## Essential git command operations
- ###### git init
- Will initialized a local repository in current directory.
```
git init
```
- ###### git config
- Will setup the username and email throughout the whole machine. check how to setup git below.

- ###### git add
- Will moved the files in youre working area into staging area.
```
git add .
```
- ###### git status
- Will check if you have unstaged files and uncommited files.
```
git status
```
- ###### git restore
- Will restore modified files into the last commit version of the file.
```
git restore .
```
- ###### git commit
- Will moved the staged files into local repository to be saved permanently.
```
git commit -m <commitMessage> 
```
- ###### git log
- Will see all the commit history
```
git log
```
- ###### git clone
- Will clone a public repository in your local machine literally just downloading a project from github.
```
git clone <gitHubLink> 
```
- ###### git push
- Will saved all the files in youre local repo into remote repo.
```
git push origin <remoteRepoDefaultBranchName>
```
- ###### git pull
- Will pull the latest changes of code from remote repo into your local repo.
```
git pull origin <remoteRepoDefaultBranchName>
``` 
- ###### git branch will list all available branch in your local repo
```
git branch
```
- ###### git checkout
- Will switch into another branch.
```
git checkout <branchName>
```
- ###### git checkout with new branch
- Will create a new branch from the current branch.
```
git checkout -b <branchName>
```
- ###### git merge
- Will merge the specified branch with the current branch
```
git merge <otherBranchToBeMergeInCurrentBranch>
```  
- ###### git remote
- Will connect to a remote repository
```
git remote add origin <gitHubLink> 
```

## Other essential git command

# VCS(Version Control System) 
- Is a system that records changes to a file or set of files overtime. So that you can recall specific version later.

# Git Software Installation
##### Git Server
- It is a repository.
- It is the largest host of source code in the world.
- It is used to store/ maintain the source code of the project.

- #### Git Server Tools:
- ###### GitHub(✅)
- ###### BitBucket
- ###### GitLab
- ###### GitBlit

##### Git Client
- Used to access the git server tools
- Can be dowloaded in [https://git-scm.com/download/win]

- #### Git Client Tools:
- ###### Git Bash(✅)
- ###### Git GUI
- ###### Git CMD
- ###### Github Desktop

# Git Architecture
![image](https://github.com/Elleined/git-github-notes/assets/111877930/3969a84f-6d71-44f4-acb9-cb0d2b9354e0)
- **Working area**: It is you're local project that the developer is working on.
- **Stage area**: This will be the bridge to your working area to local repository. Means that the files in staging area are candidate to be saved in local repository.

- **Local Repository**: Now that youre files is in local repository all files in here are candidate for moving into remote repository which is the git server like github.

###### Note: we cannot skip even one process it strictly first in working area then staging area then local repository then remote repository.

# Setting up git in you machine
- Install git from link above(Next, next no other config while installing)
- Open git bash(Anywhere directory in your machine)
- run this command
```
git config --global user.name <yourGithubUsername>
```
```
git config --global user.email <yourRegisteredEmailInGithub>
```

# Basic file workflow
- Add the newly created in stage area by executing this command.
```
git add.
```
- Commit the staged files to be saved in local repository by executing this command.
```
git commit -m <commitMessage>
```
- Push the files in your local repository in remote repository.
```
git push origin <remoteRepoDefaultBranchName>
```
