---
title: Library Carpentry Week Three Versioning Data with Git
---

Schedule:

* 17:45-18:25 Git and Github 
* 18:30-19:25 Github pages and Markdown
* 19:30-20:25 Practice and/or discussion 

---

### Basics - navigating the shell

**`pwd`** print working directory

**`ls`** list directory

- `-l`: list file information
- `-lh`: list human readable file information

**`cd`** change directory

______
### Basics - interacting with files

**`mkdir`** make directory

**`cat`** send file or files to output (in most cases, print to shell)

**`head`** output first parts of a file or files

**`tail`** output last parts of a file or files

**`mv`** rename or move a file or files. Syntax for renaming a file: `mv FILENAME NEWFILENAME`

**`cp`** copy a file or files. Syntax: `cp FILENAME NEWFILENAME`

**`>`** redirect output. Syntax with `cat`: `cat FILENAME1 FILENAME2 > NEWFILENAME`

**`rm`** remove a file or files. NB: *USE WITH CAUTION!!!*

---

### Basic Git commands 

**`git init`**: creates a git repository

**`git status`** : view the status of your files in the working directory and staging area

**`git add`**: tells git to start tracking a file, or a series of files. 

**`git commit`**: commits 'saves' the staged snapshot to the project history. 

**`git push`**: commits the staged snapshot to the project history.

**`git diff`**: shows changes made to files

**`git pull`**: Merges upstream changes into your local repository 

**`git remote add origin`**: add a repository where changes will be stored -

---

### Exercise our first git repository
We will try and do this session as a group but if prefer to go at a slower pace please follow the instructions on the week three library carpentry github page.  

### Exercise - visualising git

In groups work spend some time trying to illustrate some of the commands we've used with Git:

* try and express git commands in a non 'git' way
* try and visualise what commits are doing to your repository 

If you want to practice more feel free to keep practicising making changes to your file and committing the changes. If you want to explore more git commands search for some more online or follow one of the suggested links below.


### Exercise - contributing to a github pages site

To practice using Git, Github pages and Markdown we can contribute to a Github pages site. This page is currently very bare but we can change that by making some pull requests and suggesting changes.

#### pull-request (slightly easier way)
1. Navigate to the https://github.com/davanstrien/week-three-library-carpentry
2. Click on 'fork' repository. You will then be asked to choose where to 'fork' your repository. 
3. Once we have our own fork we can edit files directly from the github site. This is a good chance to practice some markdown syntax. You can preview how it will look before you commit changes.NB this is 'github' flavour of markdown, there are slight differences between different 'flavours'. 
4. Once we have done this we can commit our changes. 
5. If we've made some changes which we think would be worth adding to the original site then we can make a pull request. This slightly confusing terminology basically means you are asking the owner of the original source if they would like to add (pull) some of your changes into their version. 
6. Click on compare changes. This will show you if there are any differences between the two version you have. From here we can make a pull request.
7. When we make a pull request we have the option of explaining what the pull request relates to. It is important we try and give a short concise expanation of what it is about.    

#### pull-request (slightly more complicated way)
* instead of making edits on the github website you can 'clone' the repository to your local machine. 
* follow steps 1 and 2 above. 
* then follow the steps outline here: http://www.thinkful.com/learn/github-pull-request-tutorial/Writing-a-Good-Commit-Message





