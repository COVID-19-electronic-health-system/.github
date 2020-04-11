# Contributing to CoronaTracker

## TODO

- [ ] check for blank links: ()
- [ ] check repo vs respository
- [ ] review front end / back end instructions
    - idea here was to split from main contrib file for simplicity (and to make universal across all repos)
    - if someone is working on front end of CoronaTracker, would visit /client README for further instruction
    - if someone is working on back end of CoronaTracker, would visit /server README for further instruction

## Table of Contents

<!-- TOC -->

- [About the Project](#about-the-project)
  - [Project Values](#project-values)
  - [Townhall Meetings](#townhall-meetings)
- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features / Enhancements](#suggesting-features--enhancements)
  - [Contributing Code](#contributing-code)
  - [Staying Up to Date](#staying-up-to-date)
- [Style Guides](#style-guides)
  - [Naming Git Branches](#naming-git-branches)
  - [Creating Git Commit Messages](#creating-git-commit-messages)
  - [Front End Style Guide](#front-end-style-guide)
- [Getting Support](#getting-support)

<!-- /TOC -->

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

- __Check the README__ for a list of common questions, abstracts, concerns, etc.
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

> __Pro tip:__ If you prefer to [use SSH on Github](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh), remember to update the links above to the SSH versions!

5. [Create and checkout new branch](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches) in your local project to start making changes.
e.g. `git checkout -b <branch-name>`
_Note: the `-b` is only required when first creating the branch (combines `git checkout` and `git branch`)_
6. If working on the Corona-tracker app specifically, review and follow the documentation for the [Front End Configuration]() or [Back End Configuration]() depending on the type of changes you intend to make.
7. Make changes in your local project, including adding files or updating existing code.
8. Add the changed files and create a commit message describing the changes.
e.g. `git add README.md` or `git add -A` for all changed files
e.g. `git commit -m "update table of contents in readme"`
_Note: more information on [writing a good commit message](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) can be found in the linked article_
9. Continue with 6 and 7 above until all changes are complete.

__When the changes are complete and you are ready to submit them to our project__, please follow the additional steps below.

10. Check that all of your submissions follow the relevant [Style Guides](#style-guides).
11. Push the changes to the origin repository on Github (your fork).
`git push -u origin <branch-name>`
_Note: the `-u` is only required when first pushing a new branch to the origin (your fork)._
12. On github, [submit the pull request (PR)](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) to the upstream repository when changes are complete.
13. Follow all of the instructions in the [Pull Request Template]().

### Staying Up to Date

__It is important to always work from the most up to date code in our repository.__ Before making any changes, always be sure that your local repository contains the most recent changes from the upstream repository (our project).

To update your local repository, follow the steps below.

1. Check what branch you are currently working on.
`git status`
2. Check out the master branch of your local repository.
`git checkout master`
3. Fetch changes from the upstream master repository (ours).
`git fetch upstream master`
4. Rebase the changes from the upstream master respository into your local repository.
`git rebase upstream/master`
5. Check out a new branch to make and submit changes, following the procedures in [Contributing Code](#contributing-code) starting from Step 5.

## Style Guides

### Naming Git Branches

__Use the branch naming structure of "verb/intent"__, and examples are listed below. This helps make branch names easier to read, understand, and follow for the project maintainers.

```
upd/resource-list
feat/omni-auth
fix/auth-flow
```

### Creating Git Commit Messages

__Keep git commit messages short, simple, and informative__, ideally under 50 characters.

__Write commit messages in the imperative__, using "fix bug" and not "fixed bug" or "fixes bug". This convention matches up with commit messages generated by commands like `git merge` and `git revert`.

`git commit -m "update contributing.md with new sections"`

### Front End Style Guide

📝 Use Material-UI to build and style components.

📝 When styling, use Material-UI styling APIs.

🛑 Don’t use separate CSS file or inline-style i.e. “style={{width:’100px’}}"

📝 We already included ThemeProvider and CssBaseline APIs. Please use it to advantage of full Material-UI options and not worry about styling every little aspect.

📝 Use Material-UI `Typography` with `variant='x'` where x stands for ` h1,....h6, subtitle1, subtitle2, body1, body2` you can check the sizes on `Layout.jsx` components

📝 Use Material-UI breakingpoints i.e. `[theme.breakingpoints.up('md'):{width: '100px'} ` and they are as followed`keys:[xs: 0, sm: 479, md: 839,lg: 1279, xl: 1599]` So when using `[theme.breakingpoints.` with ` .down(key)]: .up(key)]: .between(start, end)]: .only(key)]: ` you need to consider these points.

📖 Material-UI has great documentation. There are a lot of examples and answers to many questions you may face from the community. You also can ask for help via Discord in the #front-end chat.

## Getting Support

__We are here to help!__ If you have questions or run into issues, please reach out to us on [our Discord server]().

We also have some [support documentation]() on common commands, common terminology, the general workflow, and a list of useful resources covering each topic above.

_If you made it to the end of this document, thank you, and we look forward to working with you and seeing your submissions!!_
