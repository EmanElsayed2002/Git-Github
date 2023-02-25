# What is source code management
- is a system that records changes to a file or set of files over time so that you can recall specific versions later
- (source code management)SCM tools are used to track revisions of source code and coordinate work among multiple developers

# What is Git
- Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people


# What is Github
- GitHub is a web-based hosting service for version control using Git
- It offers all of the distributed version control and source code management functionality of Git as well as adding its own features
- It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project

# What is the difference between Git and GitHub
| Git | GitHub |
| --- | --- |
| is a version control system | is a web-based hosting service for version control using Git |
| is a software | is a service |
| is a command line tool | is a web-based graphical interface |
| is installed on your computer | is hosted on the internet |
| Cit is maintained by Linus Torvalds | GitHub is maintained by Microsoft |
| Focused on version control and code sharing | Focused on Centralized source code hosting |
| is released 2005 | is released 2008 |

# How to create a repository
- Create a new repository on GitHub
 - Click to Repository
    - Click to New
            - add repository name
            - add description (optional)
            - select public or private
                - click to create repository

## What is README.md
- README.md is a file that contains information about the project


## How to write a good README.md
- Write a good README.md
    - Write a good title
    - Write a good description
    - Write a good installation
    - Write a good usage
- And Learn markdown language to write a good README.md syntax or use it to help him to write a good README.md
    - https://www.markdownguide.org/basic-syntax/

## What is Commit
- Commit is a save point in Git and GitHub

## How to cmmmit
- git add .  // add all files
- git commit -m "message"  // commit with message
- git push origin master  // push to github

## How to write helpful commit messages
- you should select a message that is consistent with the changes you made because it will help you to understand what you did in the future and come back to it

## What is Branch
- Branch is a way to work on different versions of a repository at one time

## How to create a branch
- git branch branch_name  // create a branch
- git checkout branch_name  // switch to branch
- git checkout -b branch_name  // create and switch to branch (abbreviated)


## How to delete directory in my Repo
- git rm -r directory_name  // delete directory

## How to push a branch to GitHub
- git push origin branch_name  // push branch to github

## How to pull updates
- git pull origin master  // pull updates from github


## How to merge branches
- git checkout main  // switch to main branch
- git merge branch_name  // merge branch to main

## How to delete a branch
- git branch -d branch_name  // delete branch

## What is Pull Request
- Pull Request is a way to tell others about changes you've pushed to a branch in a repository on GitHub

## How to create a Pull Request
- Click to Pull Request
    - Click to New Pull Request
        - Click to Create Pull Request
            - Click to Create Pull Request

## How to merge a Pull Request
- Click to Pull Request
    - Click to Merge Pull Request
        - Click to Confirm Merge

## How to work as collaborators on a project
- Click to Settings
    - Click to Manage Access
        - Click to Invite a collaborator
            - add collaborator username
            - select permission
                - click to Invite collaborator

## Which files should and which files should not appear in your repository
- Files that should not appear in your repository
    - .gitignore
    - .gitattributes
    - .gitkeep
    - .gitmodules
    - .gitco
    - .gitconfig
