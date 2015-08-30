## Library Carpetry. Week Three: Git

**Notes: set up website before hand**


### Hour One
- What is Git. What is GitHub. Basic language. Doing the basics.
- *Lesson based on Software Carpentry, [Version Control with Git](https://github.com/swcarpentry/git-novice) ([Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/))*
- the problem? loose changes, collaboration, different versions?
- solution: Version control?

### What is Git? 

Git is a 'free and open source distributed version control system'. We probably know what free and open source means but we might be less sure about what a 'distributed version control system is'. One way to understand what Git and version control systems do is to look at the types of problems they are built to address. 

![PhD comics](http://www.phdcomics.com/comics/archive/phd101212s.gif)

Many of us will have had an experience similar to this. We are working on an important piece of work and we attempt to maintain multiple version of this document in different stages of completeness. 

Version control addresses this problem by recording the changes we make to a document as we proceed. Each of the 'commits' we make is recorded and we can go back across a document or a set of documents and look at what changes have been made. 

Version control allow us to take this one step further and not only record changes to a document one person is working on but allows multiple people to work on a document and record the changes they make. It is then possible to merge these multiple documents. This developed out of a need for groups writing code together to be able to work on coding projects together without having to wait for someone else to finish working on something or having to manually compare changes that are made. 

When we make 'commits' we record a range of metadata about that change. As librarians we might already be inclined to think creating metadata is useful but an example of what information is recorded will illustrate why the information recorded by version control systems in particular is useful. 'Commits' record the time and date of when a commit was made. Although we can often see inforamtion about when we last edited or saved a document this only shows us the most recent changes. When we make commits we can record a message explaining what changes we have made. This makes it especially useful for collaborating. Rather than sending an email with a document with track changes and some comments, we can include all that information with the document itself. This makes it easy to get an overview of changes that have been made to a document by looking at a log of all the changes that have been made. 

### Git vs. Github vs. Gitlab

We often hear the terms Git and Github used interchangeably but the are slightly different things. Git refers to the software and principles used for a particular flavour of version control (there are other systems like mercurial and SVN). Github is a popular site which hosts git repositories. The majority of the content that Github hosts is open source software though increasingly it is being used for other projects such as open access journals and constantly updated text books. Github is a great place to learn how to use Git but once you have learned the ideas and processes behind github you can used Git on other storage systems or host repositories on your own server if you wanted to keep code private or you wanted to encrypt your repository. 

### Using Git 
One of the main barriers to getting started with git is the language. Although some of the language used in Git is fairly self explanatory other terms are not so clear. The best way to get to learn Git language is to begin using it but having an overview of the language and way Git is used will provide a good starting point. 

#### Some basics 

<!Should this section include initi repo etc?>

**Repository** A repository is the place where are projects and associated changes are stored. Repositories can contain one single readme file or hundreds of different folders making up the source code for extensive projects. We can create repositories in a number of different ways; we can make our own from scratch, we can fork (copy) an existing repository or we can create a git repository from an existing folder we have been working on. 

<!#### Initiate (create) a repository (init)

~~~
$ mkdir git_test
$ cd git_test
$ git init
~~~
>

#### Work through some commands online
[https://try.github.io/]()
 

Git cheat sheet handouts
* https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf 
* http://www.git-tower.com/blog/git-cheat-sheet/



---
### Hour Two
- Collaborating in groups to build a Github Pages site: who they are, what they think they could use GitHub for **setup a template for use beforehand?**
- *Lesson based on Software Carpentry, [Version Control with Git](https://github.com/swcarpentry/git-novice) ([Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)). To be worked on by [@davanstrien](https://github.com/davanstrien)*

## Github Pages

Github Pages are websites hosted on Github. They allow you to build a repository that displays as a website. Github pages uses Jekyll, a 'blog aware static site generator' to turn a site of files and folders into a webpage. 

### Why Github pages are awesome!

Github pages allow you to version control your website. This is useful for a lot different reasons. It allows you to keep a record of what changes you have made. It allows people to reference your website at a particular point in time and (if you make you're source open) to see what it was like at that particular point in time. This is very useful for academic citations. Most people have had the experience of following up a reference to a website and either getting a 404 error or seeing something completely different. Although using version on your site doesn't guarantee this won't happen it does make it easier to manage old versions of your site. 

Github pages also mean that you can collaborate on a website with a lot of people without everyone having to communicate back and forwards about what changes need to be made, or have been made already. You can create 'issues' (things that need fixing), list things to do in the future and allow other people visiting your website to quickly suggest, and help implement changes through pull requests. 

### Setting up a Github page 

Suggestions on repositories to fork (is it important to use command line?)


* https://github.com/barryclark/jekyll-now 

- [Hyde](https://github.com/poole/hyde) by MDO
- [Lanyon](https://github.com/poole/lanyon) by MDO
- [mojombo.github.io](https://github.com/mojombo/mojombo.github.io) by Tom Preston-Werner
- [Left](https://github.com/holman/left) by Zach Holman
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) by Michael Rose
- [Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll) by Michael Rose

Clone Repository 
Add some content 

* in Groups make sure everyone tries committing - pulling changes to their computer 
* demonstrate how pull requests can be discussed. 

* guidelines handout 
* step by step 

### Hour Three
- Reflecting on what GitHub could be used for in local library setting. Free time to exploring more Software Carpentry lessons and adapting forked repo with suggestions for future Library Carpentry

user contribution to collections?
- editing of resources?
- crowd sourcing - could be an issue?
- making pull requests. 
- open access journals 

### Install for Week Four
- [Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Open Refine 2.6](http://openrefine.org/download.html)
