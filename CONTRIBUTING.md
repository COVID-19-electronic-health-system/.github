# Contributing to CoronaTracker

## Table of Contents

__INSERT TOC__

## About the Project

❤️ By the community, for the community. ❤️

We are building an open source progressive web application to help reduce the number of unnecessary hospital visits, educate the public on facts vs myths, and provide a health and well-being chart for logging their journey during the Coronavirus (COVID-19) pandemic.

### Project Values

Our mission is to develop social good through technology. We value initiative, collaboration, experimentation, and integrity.

We are a welcoming, warm, and collaborative group of people from all over the world! Here you can experiment and take chances.

To FAIL is to make your First Attempt In Learning, and we are here to help. We encourage developers to learn new concepts and best practices while collaborating on a project that is scaling to help mankind against COVID-19.

### Townhall Meetings

We hold weekly townhall meetings on Saturdays, from 12:00pm EST to 12:30pm EST.

The typical agenda is:

1. Team leads will give an update
2. Discuss project roadmap
3. Discuss project deadlines
4. Discuss action items for current goals

If you have any questions or need any additional information, please discuss it with the team [on our Discord server.]()

## How to Contribute

### Reporting Bugs

This section guides you through submitting a bug report for a CoronaTracker repository. Bugs are tracked as [Github Issues](https://guides.github.com/features/issues/) and when creating a new issue you will choose from a template that gives you guidelines on what information to provide.

Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports (if applicable).

__Before creating a bug report__, please check the list below as you might find out that you don't need to create one.

1. __Check the README__ for a list of common questions, abstracts, concerns, etc.
- __Search the ISSUES__ to see if the problem has already been reported. If it has __and the issue is still open__, add a comment to the existing issue instead of opening a new one.

> __Note:__ If you find a __Closed__ issue that seems like it is the same thing that you are experiencing, __open a new issue__ and include a link to the closed issue in the body of your new one.

__When you are creating a bug report__, please include as many details as possible and fill out the required issue template. The information it asks for helps us resolve issues faster. Use the outline in the issue template to explain the problem and include additional details for maintainers.

### Suggesting Features / Enhancements

This section guides you through submitting a feature request for CoronaTracker, including completely new features or minor improvements to existing functionality. Feature requests are tracked as [Github Issues](https://guides.github.com/features/issues/) and when creating a new issue you will choose from a template that gives you guidelines on what information to provide.

Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

__Before creating a feature request__, please __search the ISSUES__ to see if the feature has already been requested. If it has __and the issue is still open__, add a comment to the existing issue instead of opening a new one.

> __Note:__ If you find a __Closed__ issue that seems like it is the same thing that you are experiencing, __open a new issue__ and include a link to the closed issue in the body of your new one.

__When you are creating a feature request__, please include as many details as possible and fill out the required issue template. The information it asks for helps us resolve issues faster. Use the outline in the issue template to explain the feature and include additional details for maintainers.

### Contributing Code

This section describes how our workflow operates so that you can contribute code in a way that scales with a growing team and product.

This represents a standard way that many open source projects operate, and more information including terminology and helpful commands can be found in the [SUPPORT.md]() file.

> ⚠️ __Please do not clone directly from our main repository.__ This will point your local repo's [origin](https://www.git-tower.com/learn/git/glossary/origin) to our main repo, and you will not have write access. Doing so will eventually cause an error when attempting to push your changes.

__When you are first setting up the repository__, follow the steps below to ensure that your changes can be merged into the project.

1. [Fork the repository](https://help.github.com/en/github/getting-started-with-github/fork-a-repo), which creates a copy of the repository under your github account to submit changes to.
2. [Clone the forked repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) to your computer using the __Clone or download__ button and the address from github.
e.g. `git clone https://github.com/YOUR_USERNAME/Corona-tracker.git`
3. Change the working directory to your cloned project.
Mac/Linux: `cd ./Corona-tracker`
Windows: `cd .\Corona-tracker`
4. [Add a remote](https://help.github.com/en/github/using-git/adding-a-remote) link to our project repository in order to track changes.
e.g. `git remote add upstream https://github.com/COVID-19-electronic-health-system/Corona-tracker.git`
5. [Create and checkout new branch](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches) in your local project to start making changes.
e.g. `git checkout -b <branch-name>`
_Note: the `-b` is required when first creating the branch (combines `git checkout` and `git branch`)_
6. Make changes in your local project, including adding files or updating existing code.
7. Add the changed files and create a commit message describing the changes. __Repeat this process for all changes.__
e.g. `git add README.md` or `git add -A` for all changed files
e.g. `git commit -m "update table of contents in readme"`
_Note: more information on [writing a good commit message](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) can be found in the linked article_

> __Pro tip:__ If you prefer to [use SSH on Github](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh), remember to update the links above to the SSH versions!

___When the changes are complete and you are ready to submit them to our project__, [squash the commits](https://github.com/servo/servo/wiki/Beginner's-guide-to-rebasing-and-squashing#squashing) using [git rebase](https://github.com/servo/servo/wiki/Beginner's-guide-to-rebasing-and-squashing#rebasing).
e.g. `git rebase -i` which brings up your text editor with a reference to your recent commits (X and Y below)
```
pick 7de252c X
pick 02e5bd1 Y

# Rebase 170afb6..02e5bd1 onto 170afb6 (2 command(s))
#
# Commands:
# p, pick = use commit
# r, reword = use commit, but edit the commit message
# e, edit = use commit, but stop for amending
# s, squash = use commit, but meld into previous commit
# f, fixup = like "squash", but discard this commit's log message
# x, exec = run command (the rest of the line) using shell
# d, drop = remove commit
#
# These lines can be re-ordered; they are executed from top to bottom.
#
# If you remove a line here THAT COMMIT WILL BE LOST.
#
# However, if you remove everything, the rebase will be aborted.
#
# Note that empty commits are commented out
```
_Note: Squashing your commits means reducing all your local commits to one single commit that will be placed in our repo's git history. This keeps our history clean and easy to read._
9. first push the changes to the origin repository on Github (your fork).
`git push -u origin <branch-name>`
_Note: the `-u` is required when first pushing a new branch to the origin (your fork)._
8. On github, [submit the pull request (PR)](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) to the upstream repository when changes are complete.

## Style Guides

## Getting Support
