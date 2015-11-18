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

**`git remote add origin`**: add a repository where changes will be stored
    - We will use `git remote add origin <https://github.com/user/repo.git>`
---

### Exercise our first git repository
We will try and do this session as a group but if prefer to go at a slower pace please follow the instructions on the week three library carpentry github page.  

### Exercise - visualising git

In groups work spend some time trying to illustrate some of the commands we've used with Git:

* try and express git commands in a non 'git' way
* try and visualise what commits are doing to your repository 

If you want to practice more feel free to keep practicising making changes to your file and committing the changes. If you want to explore more git commands search for some more online or follow one of the suggested links below.

### Exercise - contributing to a github pages site

<!TO DO> 

- pull requests 
- set up site to pull from
- outline some activities for interacting with github pages 
- instructions for pull requests 
- Pull request 'in browser' and by forking

### Further reading 

* https://help.github.com/
* https://guides.github.com/activities/hello-world/
* https://www.atlassian.com/git/tutorials


