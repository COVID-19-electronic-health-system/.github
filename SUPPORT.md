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
  - [Amazon Web Services (AWS)](#amazon-web-services-aws)
  - [MongoDB](#mongodb)
  - [Material UI](#material-ui)
  - [React](#react)
  - [Jest](#jest)
  - [Golang](#golang)
  - [Git / Github](#git--github)

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

**[Corona-tracker:](https://github.com/COVID-19-electronic-health-system/Corona-tracker)** CoronaTracker is an easy-to-use and accessible progressive web application that helps you monitor your wellness and stay informed during the COVID-19 crisis, designed by an open-source community invested in public health.

**[Coronalert:](https://github.com/COVID-19-electronic-health-system/Coronalert)** CoronaTracker notification service

**[Coronalytics:](https://github.com/COVID-19-electronic-health-system/Coronalytics)** CoronaTracker analytics service

**[Coronadvise:](https://github.com/COVID-19-electronic-health-system/Coronadvise)** CoronaTracker education service

**[.github](https://github.com/COVID-19-electronic-health-system/.github):** Community health files for the [@COVID-19-electronic-health-system](https://github.com/COVID-19-electronic-health-system) organization.

**[PanFLUte:](https://github.com/COVID-19-electronic-health-system/PanFLUte)** An open source spirometer for everyone.

### Technology Stack

- Frontend: [React](https://github.com/facebook/react)
- Backend: [Blockstack](https://blockstack.org/about)
- Database: [Gaia](https://github.com/blockstack/gaia) and [MongoDB](https://www.mongodb.com/cloud/atlas)
- Deployment: [AWS](https://aws.amazon.com/)

## Blockstack Resources

Blockstack is a decentralized computing platform that promotes "privacy by design". We chose to use Blockstack so that users own their health data and their identity.

To learn more about Blockstack, [visit their website](https://blockstack.org/about), view the [Blockstack FAQs](https://docs.blockstack.org/faqs/allfaqs), or view the [technical whitepaper](https://blockstack.org/whitepaper.pdf).

## Common Commands

### Git

**Information**

- Show the working tree status
  `git status`
- show the current HEAD and its ancestry
  `git log`
- show the current HEAD and its ancestry with formatting
  `git log --pretty=format:"%h %s" --graph`
- show an ordered list of the commits that HEAD has pointed to (a local undo history for your repo - [reference](https://stackoverflow.com/questions/17857723/whats-the-difference-between-git-reflog-and-log))
  `git reflog`
- show all branches
  `git branch -a`
- list remote repositories
  `git remote -v`
- show line-by-line changes in your branch compared to master
  `git diff`

**Make Changes**

- Create new branch to make changes
  `git checkout -b <branch>`
- Checkout branch to make changes
  `git checkout <branch>`
- Change file name
  `git mv <old-file> <new-file>`
- Delete file
  `git rm <file>`

**Commit Changes**

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

**Update the Repo**

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

**Delete Branch**

- Delete the branch from origin
  `git push origin -d <branch>`
- Delete the branch from local
  `git branch -d <branch>`

### Yarn

[Full list of yarn commands](https://classic.yarnpkg.com/en/docs/cli/)

`yarn install`

- Install all node modules
- Similar to `npm i`
- [More Info](https://classic.yarnpkg.com/en/docs/cli/install)

`yarn add`

- Installs a package and any packages that it depends on
- Similar to `npm install <package-name>`
- [More Info](https://classic.yarnpkg.com/en/docs/cli/add)

`yarn remove`

- Removes an unused package from your current package.json
- Similar to `npm uninstall <package-name>`
- [More Info](https://classic.yarnpkg.com/en/docs/cli/remove)

`yarn init`

- Initializes the development of a package.
- Similar to `npm init`
- [More Info](https://classic.yarnpkg.com/en/docs/cli/init)

`yarn upgrade`

- Upgrades packages to their latest version based on the specified range
- Similar to `npm update <package-name>@<verision>`
- [More Info](https://classic.yarnpkg.com/en/docs/cli/upgrade)

## General Resources and Links

### Amazon Web Services (AWS)

- AWS: [Getting Started Resource Center](https://aws.amazon.com/getting-started/)
- Udemy: [AWS Certification Courses](https://www.udemy.com/topic/aws-certification/)
- PluralSight: [AWS Paths and Courses](https://www.pluralsight.com/search?q=aws)

### MongoDB

- MongoDB: [Getting Started](https://docs.mongodb.com/manual/tutorial/getting-started/)
- Udemy: [MongoDB Courses](https://www.udemy.com/topic/mongodb/)
- PluralSight: [MongoDB Paths and Courses](https://www.pluralsight.com/search?q=mongodb)

### Material UI

- Material UI: [Installation](https://material-ui.com/getting-started/installation/) and [Usage](https://material-ui.com/getting-started/usage/)
- Material Design: [Color System](https://material.io/design/color/)
- Material Design: [Accessibility](https://material.io/design/usability/accessibility.html)
- Udemy: [Material UI Courses](https://www.udemy.com/topic/material-design/)

### Styled-Components

Use the best bits of ES6 and CSS to style your apps without stress 💅. Useful to containerize our apps style along with our components.

- [Documentation](https://styled-components.com/docs)

### React

- Tutorial: [Intro to React](https://reactjs.org/tutorial/tutorial.html)
- Udemy: [React Courses](https://www.udemy.com/topic/react/)
- PluralSight: [React Paths and Courses](https://www.pluralsight.com/search?q=react)

**React-Router-Dom**

DOM bindings for React Router. Used to change views on client side.

- Tutorial: [React Training / React Router Quick Start](https://reacttraining.com/react-router/web/guides/quick-start)

### Redux

- Tutorial: [Getting Started with Redux](https://redux.js.org/introduction/getting-started)
- Udemy: [Redux Framework Courses](https://www.udemy.com/topic/redux-framework/)
- Pluralsight: [Redux Paths and Courses](https://www.pluralsight.com/search?q=redux)

**Redux-Thunk**

Used to manipulate state before calling dispatch() to Redux's state

- Documentation: [reduxjs/redux-thunk repo](https://github.com/reduxjs/redux-thunk)

### Axios

Promise based HTTP client for the browser and node.js

- [Documentation](https://github.com/axios/axios)

### Jest

- Jest: [Getting Started](https://jestjs.io/docs/en/getting-started.html)
- PluralSight: [Testing React Applications with Jest](https://www.pluralsight.com/courses/testing-react-applications-jest)

### Golang

- Go: [Getting Started](https://golang.org/doc/install)
- Udemy: [Go Programming Language Courses](https://www.udemy.com/topic/go-programming-language/)
- PluralSight: [Go Paths and Courses](https://www.pluralsight.com/search?q=golang)

### Git / Github

**Git Resources**

- [Git Command Reference](https://git-scm.com/doc)
- Git Tower: [Learn Version Control with Git](https://www.git-tower.com/learn/git/ebook/en/command-line/introduction)
- Git Tower: [What is a rebase in Git?](https://www.git-tower.com/learn/git/glossary/rebase)
- Git Tower: [`rebase` as an alternative to `merge`](https://www.git-tower.com/learn/git/ebook/en/desktop-gui/advanced-topics/rebase#start)
- Atlassian: [Overview of `rebase`](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)
- Github Help: [How to use `rebase`](https://help.github.com/en/github/using-git/using-git-rebase-on-the-command-line)
- [Learning Git Branching](https://learngitbranching.js.org/?locale=en_US)
- [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
- [Oh Shit, Git!?!](https://ohshitgit.com/) with real problems and solutions

> ⚠️ 👀 **WARNING:**
> You should use rebase only for squashing YOUR local commits prior to a pull request. DO NOT ever to rebase commits that have already been published to master. This will rewrite our public project's history. This applies to maintainers of the project.

**Github Resources**

- Github Guides: [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
- [GitHub Standard Fork & Pull Request Workflow (Chaser324)](https://gist.github.com/Chaser324/ce0505fbed06b947d962)
- [Digital Ocean - How To Create a Pull Request on GitHub](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github)
- Mozilla Servo: [Beginner's guide to rebasing and squashing](https://github.com/servo/servo/wiki/Beginner's-guide-to-rebasing-and-squashing)
