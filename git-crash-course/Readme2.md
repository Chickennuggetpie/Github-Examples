## Git Hidden Folder

there is a hidden folder called .git that tells you that your project is a git repo 

If we want to create a git repo in a different project, we create the folder and initialize the repo using git init

```
mkdir /workspaces/tmp/new-project
cd /workspaes/tmp/new-project
git init
touch Readme.md
code Readme.md
git status
git add Readme.md
# make changes to readme.md 
git commit -a -m "add readme file" 
```

## cloning

we can clone three ways: HTTPS< SSH< and Github CLI

We will create a temporary directory in our workspace 
```sh 
mkdir /workspace/tmp
cd /workspace/tmp
```

### HTTPS

```sh 
git clone https://github.com/Chickennuggetpie/Github-Examples.git
cd Github-Examples
```
## commits 

Git commit 
when we want to commit code we write git commit, which will open up the commit message in the editor of choice 

``` sh 
git commit 
```
```
git config --global core.editor emacs
```

set the global editor 

## branches 

## Remotes 

## Stashing 

## merging 

## Add
When we want to stage changes that will be included in the commit 
we can use the period to add all files 

```
git add 
git reset 
```

## status 

Git status shows you what files will or will not be commited 
```
git status
```


## Git Reset

Reset allows you to move staged changes to be unstaged 
this is useful when you want to revert all files to not be commited 

```
git add 
git reset 

When you first install git on a machine you are supposed to set up your name and email 

```sh
git config --global user.name "john doe" 
git config --global user.email johndoe@example.com