# Lesson Plan Week 2

## Agenda

The purpose of this class is to introduce to the student (1) the basics of using GIT, and (2) the basics of grid-based thinking and using flexbox:

- Basic GIT commands
- Introducing GitHub
- Setting up an SSH key pair

- Introducing grid-based thinking
- The problem Flexbox solves
- Basic flexbox commands

## Core Concepts

FIRST HALF (12.00 - 13.30)

1. **Introduction to GIT**

- GIT is software that allows us to keep track of the changes within our files
- Imagine having written complex code that messed everything up, GIT allow us to return to a previous state where everything was still working
- It can be used through the command line interface (CLI) or using a graphical user interface (also known as GUI): SourceTree, SmartGit, etc.
- GitHub is a development platform that allows us to store a copy of our code online (in developer terms: remote)
- Main benefits are (1) store our code online, (2) let's us easily work together with others in the same repository
- Explain the difference between GIT and GitHub

_Ask students to create an account on Github if they haven't_

- In order to securely use GitHub we need to create an SSH key
- SSH keys allow GitHub to identify us as a safe connection

_Create a new local repository and tell students to do the same_

_Create a sample.txt file through the CLI and commit it to the local repository_

- When you want to save your work, you can make a snapshot of your workspace: this is called 'committing your work', which is another way of saying 'saving your work'

_Create an SSH key through the CLI_

_Link the SSH key with your GitHub account_

_Do the first push so that local repo and remote repo are in sync_

- Explain the difference between local and remote


_Delete the file and commit that change_

- GIT allows us to revert our workspace to a previous commit. We can look for the right commit using `git log`, `git checkout` and `git revert`

_Show the student the process of reverting back to the first commit_


_Show the hidden file `.git` in the folder_

_Show how to clone the HTML-CSS-GIT repo using SSH_

- Explain the difference between `init` and `clone`

SECOND HALF (14.00 - 16.00)

2. **Grid-based thinking and Flexbox**

- Thinking in grids

_Look at the following [website](https://htmlstream.com/preview/unify-v2.6.2/unify-main/home/home-default.html) and dissect it thinking in grids_

- Flexbox allows us to easily align elements on the page
- It replaces float-based web design
- It is activated with the `display: flex` CSS property, after you can make use of flex-specific properties

_Take a look at the following [CodePen](https://codepen.io/enxaneta/pen/adLPwv) with students_

_Rebuild the navigation bar, center image and reponsive website layout from this [example](https://github.com/ratracegrad/made-with-flexbox)_

_Ask student to rebuild the navigation bar using Flexbox_
