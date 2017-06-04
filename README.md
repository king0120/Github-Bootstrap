# Lesson 18 - Students choice

## What did I miss?
One week until final presentation demos and the end of the course!  What will next Monday be like?

## Lesson Objectives
By the end of this class you will be able to:
* Understand the uses and advantages of using Version Control
* Differentiate between Git and GitHub
* Create a Github repository and push it to an online repo.
* Install Bootstrap and add it to an existing project
* Explain Bootstrap's 12-column grid system

Git & Github
=====

## What is Version Control?
Version control is a way to keep track your project as it changes over time.  It also is the easiest way to collaborate with other developers working on the same codebase.

Have you ever run into this problem? 
![phd version-control](phd101212s.png)
This is what version control solves.  Using version control you can incrementally change and modify your project, while still having a history of your previous work. 

#### What is Version Control good for?

Imagine these scenarios 
* You've been working on a project for weeks that you're pretty happy with.  Unfortunately, you start working on a new feature that breaks a lot of the things you were happy with.  How could you backtrack and retrieve the version you were happy with?
* You're working on a project with 3 other developers.  How do you manage who makes changes?  How to you make sure that the code one developer writes doesn't affect the code that you write?  How do you make comments and suggestions about these code changes?

## Git

[Git](https://git-scm.com/) is:

- A program you run from the command line or the desktop
- A distributed version control system

Programmers use Git so that they can keep the history of all the changes to their code. This means that they can rollback changes (or switch to older versions) as far back in time as they started using Git on their project.  

Note: We don't have enough time to talk about using Git from the command line, but I highly recommend learning how to. Github provides a great tutorial [here](https://try.github.io/).


#### Terminology/History

A codebase in Git is referred to as a **repository**, or **repo**, for short.

Repositories are kind of like "projects" in Git
  * Each repository is independent of others.
  * No specific definition, can be whatever you want it to be.
  * Usually one project per repo, e.g:
    * Relaxr Website
    * Startup MatchMaker
    * Final Project

Git is pretty confusing and complex at first, but I have full confidence that you will pick it up before you know it. When we talk about repos and codebases we're really just talking about a directory that has a file in it named .git. This .git is very importanta.  It tells git binary to treat the directory as a repo and listen for changes, track files, and do git-related tasks when asked.

Git was created by [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds), the principal developer of Linux.


## GitHub

[GitHub](https://github.com/) is:

- A hosting service for Git repositories
- A web interface to explore Git repositories
- A social network of programmers
- We all have individual accounts and put our codebases (repos, directories) on our GitHub account
- You can follow users and star your favorite projects
- Developers can access codebases on other public accounts
- You can use it to work on open source project
- GitHub uses Git

Repos exist both locally on your computer and can be pushed to services like Github for online storage.

You can "clone" repositories from github onto your computer. (Demo for class)

As you make changes, you can "commit" them to your local git folder... then "push" them to your GitHub repository

#### Can you use git without GitHub?

Think about this quote: “Git is software. GitHub is company that happens to use Git software.”  

**Exercise:** If you think this statement is true, react to with a thumbs up or a thumbs down if you think it is false. Why?

## Codealong - Set Up Github Desktop and publish your final project

* Visit [GitHub](https://github.com/) and sign up for an account.
* Download the [Desktop Client](https://desktop.github.com/) (Don't download the new Beta just yet)
* Sign into your new GitHub account through the Desktop client.
* Add your Final Project folder to GitHub by using the '+' button in the top left corner
* You will see that there are changes to be made to your git repo (because this is the first time you've made a commit)
* Create a commit message and description, then click 'commit to master'
* Now let's make some changes
  * Create a README.md file.
  * This is a file that Github uses to show text when you visit a page on Github.  Think of it as a place where you can describe what your app does, how to install it, etc.
  * .md means it is a Markdown file. Think of it as a hybrid between regular text files and html
  * [Cheatsheet here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Check out the Github Desktop again, and you'll see that it has tracked your changes.
* Let's make another commit.
* Now we have our project and a couple commits.  Let's push it to GitHub to share with others.
* Click Publish in the top right corner.
* Visit your personal GitHub page. Voila!


Bootstrap
====

## What is Bootstrap?

## Mobile First Design

## Installing Bootstrap

## 12-Column Grid

## Components




