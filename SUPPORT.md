# Support for CoronaTracker

## Table of Contents

<!-- TOC -->

- [Project Leads and Contact Info](#project-leads-and-contact-info)
  - [Anthony A (Project Organizer)](#anthony-a-project-organizer)
  - [Carter Klein: (CTO / Back End Lead)](#carter-klein-cto--back-end-lead)
  - [Brian H. Hough (UI/UX Lead)](#brian-h-hough-uiux-lead)
  - [Akil Hylton (Hardware Lead)](#akil-hylton-hardware-lead)
  - [Nick Giangre (Analytics Lead)](#nick-giangre-analytics-lead)
  - [Salvatore Volpe (Translations Lead)](#salvatore-volpe-translations-lead)
  - [Luke Lin (Discord Lead)](#luke-lin-discord-lead)
  - [Jason Schrader (Documentation Lead)](#jason-schrader-documentation-lead)
- [CoronaTracker Resources](#coronatracker-resources)
  - [Repositories](#repositories)
  - [Technology Stack](#technology-stack)
- [Blockstack Resources](#blockstack-resources)
- [Common Commands](#common-commands)
  - [Git](#git)
  - [Yarn](#yarn)
- [General Resources and Links](#general-resources-and-links)

<!-- /TOC -->

## Project Leads and Contact Info

[Join our Discord Server](https://discord.gg/pPERUuv)

### Anthony A (Project Organizer)

Also known as "The Dude", "His Dudeness", "Duder" or "El Duderino" if you're not into the whole brevity thing.

Front End Code, Documentation, and booking meetings with experts

Open to peer program any issue or bugs!

- Github: @tesla809
- Discord: @Anthony A.

### Carter Klein: (CTO / Back End Lead)

Back End, Front End, Systems Architecture

- Github: @Carter Klein
- Discord: @Carter Klein

### Brian H. Hough (UI/UX Lead)

Front End, Design, Social Media Marketing

- Github: @Brian H. Hough
- Discord: @InterstellarX

### Akil Hylton (Hardware Lead)

Front End, Documentation, Machine Learning

Open to peer program any issue or bugs!

- Github: @akilhylton
- Discord: @Akil Hylton

### Nick Giangre (Analytics Lead)

Data Models, Analytics, Data Science

See [analytics thread / issue.](https://github.com/COVID-19-electronic-health-system/Corona-tracker/issues/51)

- Github: @ngiangre
- Discord: @NickG

### Salvatore Volpe (Translations Lead)

Translations, Analytics

- Github: @salvolpe
- Discord: @laseplov

### Luke Lin (Discord Lead)

Managing Discord, Discord Roles, Front End, Translations

- Github: @lukelin1991
- Discord: @kirbypooh

### Jason Schrader (Documentation Lead)

Documentation, Documentation, Documentation

- Github: @whoabuddy
- Discord: @whoabuddy

## CoronaTracker Resources

### Repositories

__[Corona-tracker:]()__ CoronaTracker is an easy-to-use and accessible progressive web application that helps you monitor your wellness and stay informed during the COVID-19 crisis, designed by an open-source community invested in public health.

__[Coronalert:]()__ CoronaTracker notification service

__[Coronalytics:]()__ CoronaTracker analytics service

__[Coronadvise:]()__ CoronaTracker education service

__[.github](https://github.com/COVID-19-electronic-health-system/.github):__ Community health files for the [@COVID-19-electronic-health-system](https://github.com/COVID-19-electronic-health-system) organization.

__[PanFLUte:](https://github.com/COVID-19-electronic-health-system/PanFLUte)__ An open source spirometer for everyone.

### Technology Stack

- Frontend: [React](https://github.com/facebook/react)
- Backend: [Blockstack](https://blockstack.org/about)
- Database: [Gaia](https://github.com/blockstack/gaia)
- Deployment: [AWS](https://aws.amazon.com/)

## Blockstack Resources

Blockstack is a decentralized computing platform that promotes "privacy by design". We chose to use Blockstack so that users own their health data and their identity.

To learn more about Blockstack, [visit their website](https://blockstack.org/about), view the [Blockstack FAQs](https://docs.blockstack.org/faqs/allfaqs), or view the [technical whitepaper](https://blockstack.org/whitepaper.pdf).

## Common Commands

### Git

__Information__

- Show the working tree status
`git status`
- show commit logs
`git log`
- show commit logs with formatting
`git log --pretty=format:"%h %s" --graph`
- show all branches
`git branch -a`
- list remote repositories
`git remote -v`

__Make Changes__

- Create new branch to make changes
`git checkout -b <branch>`
- Checkout branch to make changes
`git checkout <branch>`
- Change file name
`git mv <old-file> <new-file>`
- Delete file
`git rm <file>`

__Commit Changes__

- Make changes to the file
`atom <filename>` _(or text editor of your choice)_
- Add a single file with changes
`git add <filename>`
- Add all files with changes
`git add -A`
- Commit the change with a message
`git commit -m "Commit Message"`
- Add all files and commit the change in one command
`git commit -am "Commit Message"`
- Modify last commit message
`git commit --amend`
- Push change to repository (on Github)
`git push origin`

__Update the Repo__

- Setting an upstream repository
`git remote add upstream <clone-link>`
- Check out the master branch
`git checkout master`
- Fetch branch from the upstream repository
`git fetch upstream <branch>`
- Rebase changes from the upstream repository
`git rebase upstream/<branch>`
- Push changes to the origin repository
`git push origin`

__Delete Branch__

- Delete the branch from origin
`git push origin -d <branch>`
- Delete the branch from local
`git branch -d <branch>`

### Yarn



## General Resources and Links

Links to get started with AWS
https://aws.amazon.com/getting-started/
https://www.udemy.com/topic/aws-certification/

Links to get started with MongoDB
https://docs.mongodb.com/manual/tutorial/getting-started/
https://www.udemy.com/course/mongodb-the-complete-developers-guide/
https://www.pluralsight.com/search?q=aws

Links to MaterialUI
https://material-ui.com/

React
[Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)
https://www.pluralsight.com/paths/react

Jest
https://jestjs.io/docs/en/getting-started.html
https://www.pluralsight.com/courses/testing-react-applications-jest

Links to get started with GoLang
https://golang.org/doc/install

Git/Github Info
[Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
[A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)

From git-tower:
"In Git, the rebase command integrates changes from one branch into another. It is an alternative to the better known "merge" command.

Most visibly, rebase differs from merge by rewriting the commit history in order to produce a straight, linear succession of commits."

See [What is a rebase in Git?](https://www.git-tower.com/learn/git/glossary/rebase)

[Overview of `rebase`.](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)

[How to use `rebase`.](https://help.github.com/en/github/using-git/using-git-rebase-on-the-command-line)

Why do we prefer rebase versus merge?
"Some people prefer to go without such automatic merge commits. Instead, they want the project's history to look as if it had evolved in a single, straight line. No indication remains that it had been split into multiple branches at some point."

⚠️ 👀 **WARNING:**
You should use rebase only for squashing YOUR local commits prior to a pull request. DO NOT ever to rebase commits that have already been published to master. This will rewrite our public project's history. This applies to maintainers of the project.

Read this EXCELLENT article on [Rebase as an Alternative to Merge](https://www.git-tower.com/learn/git/ebook/en/desktop-gui/advanced-topics/rebase#start) from git-tower.

[See Beginner's guide to rebasing and squashing.](https://github.com/servo/servo/wiki/Beginner's-guide-to-rebasing-and-squashing)
