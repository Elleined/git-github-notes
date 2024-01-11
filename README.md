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

## Essential git command operations
- ###### git help
- ###### git init
- ###### git config  
- ###### git add  
- ###### git status  
- ###### git restore  
- ###### git commit  
- ###### git log  
- ###### git clone  
- ###### git push  
- ###### git pull  
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
