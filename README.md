# Setting Up An Open Source Project

![](come-in-open-source.jpg)
[Photo Credit: Pete McCarthy](https://www.flickr.com/photos/petemccarthy/6866996865/in/photolist-bsP9VF-5HxTaS-aDjRJP-aDjQrH-deG7gC-aDoF1o-aDjPXc-aDoGmu-6rVG54-4SamTJ-aDoGf7-6rkTRy-oau5mJ-rufey1-q7f8tc-6D4R4n-ob5fBr-9ZakZE-fUg5eD-ruf1Y1-hvbS4v-afKdid-nPLGo6-p6vQv5-e28yoh-djiwmi-pPy6cL-74jKzz-nVcJqF-nQiamA-6fSXcE-aDoGyU-fAjoZM-4S4Lcz-5ZXKj8-aDjQSr-7z68V1-pPDNbq-edZStq-8f1nQ1-eVGah1-piE7UU-qzeuLm-6fSGWA-3TRAoj-8Yko35-6fSSyE-6fNEBM-fcweAo-qzfe8W)

Table of Contents
-----------------

- [About](#about)
- [Testimonials](#testimonials)
- [Documentation File Types](#documentation-file-types)
    - [Markdown](#markdown)
    - [Dotfiles](#dotfiles)
- [Initial Documentation](#initial-documentation)
    - [README](#readme)
    - [LICENSE.md](#licensemd)
    - [Wiki](#wiki)
- [Environment, Git and Editor Configs](#environment-git-and-editor-configs)    
    - [.env](#env) 
    - [.gitattributes](#gitattributes)    
    - [.gitconfig](#gitconfig)
    - [.editconfig](#editconfig)
- [Advanced Work Patterns](#advanced-work-patterns)
    - [Git Flow](#git-flow)
    - [A Successful Git Branching Model](#a-successful-git-branching-model)
    - [Semver](#semver)    
- [Release Documentation](#release-documentation)
    - [CHANGELOG.md](#changelogmd)
    - [RELEASING.md](#releasingmd)      
- [Collaboration](#collaboration)
    - [Organizations](#organizations)
    - [Teams](#teams)
    - [Tasks](#tasks)   
- [Workflow Tools](#workflow-tools)
    - [Projects](#projects) 
    - [Issues](#issues) 
    - [Milestones](#milestones)
    - [Pull Requests](#pull-requests) 
    - [Code Review](#code-review)
- [Contributing Templates](#contributing-templates)
    - [ISSUE_TEMPLATE.md](#issue_templatemd)
    - [PULL_REQUEST_TEMPLATE.md](#pull_request_templatemd)
- [Contributing Documentation](#contributing-documentation)
    - [CODE_OF_CONDUCT.md](#code_of_conductmd)
    - [CONTRIBUTING.md](#contributingmd)
    - [Styleguide](#styleguide)
- [New Contributors](#new-contributors)
- [Helpful Resources](#helpful-resources)

<hr>

# About

While looking through GitHub repositories and reading/watching coding tutorials, I have come across a number of best practices for setting up projects. I've never seen these best practices in one place, so I decided to create my own list. Though some are more common than others, a few are obscure, but highly useful! This list is fairly unopinionated. Depending on the language/framework used in a project, additional config files will be needed. 

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Testimonials

> **“Great idea and that's really useful.”**<br>
> — Jeff

> **“Cool :) This looks really useful. I'll have to follow the suggestions there.”**<br>
> — Mariatta

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Documentation File Types

## Markdown

GitHub project documentation is often created using Markdown files (files that end in .md). Markdown tends to be simpler and easier to use than regular HTML. See [GitHub flavored Markdown](https://help.github.com/articles/github-flavored-markdown) for instructions. 

## Dotfiles

Dotfiles begin with a dot and often contain configuration info specific to the developer or project. Dotfiles (or folders) are normally hidden from view. 

* [Hidden File and Hidden Directory](https://en.wikipedia.org/wiki/Hidden_file_and_hidden_directory)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Initial Documentation

## README.md

A [README](https://en.wikipedia.org/wiki/README) is a file that contains project information and instructions.  

* [Example README Structure](https://github.com/KatherineMichel/setting-up-an-open-source-project/blob/master/example-README-structure.md)

## Wiki

A README usually suffices for providing project information. If not, every GitHub repo comes with a wiki. The project wiki is enabled by default under Settings -> Features. Editing can be restricted to collaborators only. GitHub wikis can be created using [GitHub flavored Markdown](https://help.github.com/articles/github-flavored-markdown) and hyperlinks can be created across pages. 

* [GitHub Projects with Great Wikis](https://github.com/showcases/projects-with-great-wikis)

## LICENSE.md

A [Software License](https://en.wikipedia.org/wiki/Software_license) specifies the terms under which open source code can be used and redistributed. GitHub offers guidance for choosing a license. A repo that does not contain a license is considered copyrighted and therefore cannot be used publicly without permission. 

* [GitHub Choose a License](http://choosealicense.com)
* [GitHub Open Source Licensing](https://help.github.com/articles/open-source-licensing) 

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Environment, Git and Editor Configs

## .env

## .gitignore

When running code locally, some files may be generated that are only for your own local use. A .gitignore is a dotfile used to instruct Git to not include these files when pushing code to GitHub, where they would be unncessary. GitHub provides .gitignore templates that vary by language or framework. Alternatively, files to be ignored can be stores in hidden folders named .git/info/exclude. 

* [GitHub .gitignore Templates](https://github.com/github/gitignore) 
 
## .gitattributes 
 
## .gitconfig 
 
A .gitconfig is a dotfile in which a developer or project maintainers can specify local Git preferences.  
 
<!--
https://git-scm.com/docs/git-config
--> 
 
## .editconfig 
 
A .editconfig is a dotfile in which a developer or project maintainers can specify local editor preferences. For example, if developers are working on different operating systems (Linux, Mac OS, Windows), .editconfig settings can be used to standardize line endings across all machines. 
 
 * [EditorConfig](http://editorconfig.org)
 
:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr> 
 
# Advanced Work Flow

## Git Flow

* [Understanding the GitHub Flow](https://guides.github.com/introduction/flow)

## A Successful Git Branching Model

* [A Successful Git Branching Model](http://nvie.com/posts/a-successful-git-branching-model)

## Semver

* [Semver](http://semver.org)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Release Documentation

## CHANGELOG.md

A [CHANGELOG.md](https://en.wikipedia.org/wiki/Changelog) file lists notable changes made to the project. 

## RELEASING.md

A RELEASING.md file gives instructions for how to complete a software release. 

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Collaboration

## Organizations

Organization accounts are for code owned by groups (companies, OSS projects). 

* [About GitHub Organizations](https://help.github.com/articles/about-organizations)

## Teams

Teams make permission management easier. A developer added to a team now has access to repos based on team access. 

## Tasks

Backend
* Code
* Plugin/utility libraries
* Tools
* Infrastructure (Hosting, Build-Tools, etc)
* Tests
* Bug reports
* Examples
* Translation

Frontend
* Design

Support
* Reviewed Pull Requests
* Documentation
* Answering Questions (in Issues, Stack Overflow, Gitter, Slack, etc.)

Media
* Blogposts
* Tutorials
* Videos
* Talks

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Workflow Tools

GitHub provides a number of special features that help with workflow. 

* [GitHub Features](https://github.com/features)

## Projects

* [Projects](https://help.github.com/articles/tracking-the-progress-of-your-work-with-projects)

## Issues

Enable Issues to:
* Manage features
* Track bugs

Labels
* Label examples: Help Wanted, Beginner Friendly
* Label examples: Features, Bugs, Enhancements

## Milestones

## Pull Requests

## Code Review

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

<!--
Listing issues- issues tab, open/closed, filtering issues
Labels- including multiple labels
Assign, milestone, issue notifications, subscribe/unsubscribe to an issue
Respond by replying to any email about that issue

Issues- keyboard shortcuts
New issue, drop down list of developers, select/create new milestone
Rails repo issues- filter issues by milestone, labels
-->

<!--
Code Review (See also Project Management)
* [Code Review Wikipedia](https://en.wikipedia.org/wiki/Code_review)
* [List of Tools for Code Review Wikipedia](https://en.wikipedia.org/wiki/List_of_tools_for_code_review)

https://help.github.com/articles/about-repository-graphs#traffic

https://guides.github.com/features/issues
https://github.com/blog/957-introducing-issue-mentions

Milestones
https://help.github.com/articles/creating-and-editing-milestones-for-issues-and-pull-requests
https://help.github.com/articles/associating-milestones-with-issues-and-pull-requests
https://github.com/blog/2178-multiple-assignees-on-issues-and-pull-requests
-->

<!--
Repo Access
* Public repo- anyone can access
* Private repo- only collaborators

Access Control in GitHub
* Owners can do anything
* Collaborators have full read/write access (can push to the project, merge pull requests), but not administrative access (can't change settings, add new collaborators)
* If you want to restrict someone's access to commit to master branch, instead of adding them as a collaborator, ask them to fork the repo to make changes
* Have team members work on the same code base, but have separate repo that you send pull requests to that only your operations manager or team lead can accept

## Issues

Types of GitHub Comments
* On the pull request
* On the commit
* On a line

Commenting Enhancements
* @ mentioning

Mention an issue in a commit and will show up in the issue and notify anyone subscribed to issue: 

    $ git commit -m "Should help with issue #1"

Close to issue with a commit: include "fixes" "closes" or "resolves" to auto close the issue when merged in default branch (probably master)

    $ git commit -m "Fixes #1"
-->

# Contributing Templates

When an issues or pull request template is added to a repository, the template contents will automatically populate in the issue or pull request form body. These templates can be stored in the root or a hidden directory named .github.

* [GitHub Issue and Pull Request Templates](https://github.com/blog/2111-issue-and-pull-request-templates)

## ISSUE_TEMPLATE.md

* [Creating an Issue Template for Your Repository](https://help.github.com/articles/creating-an-issue-template-for-your-repository)

## PULL_REQUEST_TEMPLATE.md

* [Creating an Pull Request Template for Your Repository](https://help.github.com/articles/creating-a-pull-request-template-for-your-repository)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Contributing Documentation 
 
## CODE_OF_CONDUCT.md

A [Code of Conduct](https://en.wikipedia.org/wiki/Code_of_conduct) sets forth the standard of conduct expected of project contributors. 

* [Adding a Code of Conduct to Your Project](https://help.github.com/articles/adding-a-code-of-conduct-to-your-project)

## CONTRIBUTING.md

A CONTRIBUTING.md file provides guidance to contributors about best practices for contributing to the project. 

* [Setting Guidelines for Repository Contributors](https://help.github.com/articles/setting-guidelines-for-repository-contributors)

## Styleguide

Similarly to a journalistic styleguide, a programming styleguide illustrates the project's preferred coding conventions.

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# New Contributors

Ideally, make project welcoming to newcomers, with user-friendly documentation. 

Helpful Info
* [Helping People Contribute to Your Project](https://help.github.com/articles/helping-people-contribute-to-your-project)

Mentors
* Include mentor list if applicable

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Helpful Resources

* [GitHub Blog](https://github.com/blog) 

Git and GitHub Documentation
* [Git Homepage](https://git-scm.com)
* [Set Up Git](https://help.github.com/articles/set-up-git)
* [Try Git](https://try.github.io)
* [GitHub Help](https://help.github.com)  
* [GitHub Training](http://training.github.com)  
* [GitHub Bootcamp](https://help.github.com/categories/bootcamp)  
* [GitHub Guides](https://guides.github.com) 

Git Cheat Sheets and Tutorials 
* [GitHub Development Git Cheat Sheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf) 
* [GitHub Hello World Tutorial](https://guides.github.com/activities/hello-world)
* [Atlassian Git](https://www.atlassian.com/git) and [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)  
* [Digital Ocean Git Tutorial Series](https://www.digitalocean.com/community/tutorial_series/introduction-to-git-installation-usage-and-branches)
* [Bitbucket Learn Git with Bitbucket Cloud](https://confluence.atlassian.com/bitbucket/tutorial-learn-git-with-bitbucket-cloud-759857287.html) 

GitHub Markdown Documentation
* [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown) 
* [GitHub Mastering Markdown Tutorial](https://guides.github.com/features/mastering-markdown)

Fantastic README Examples
* [Awesome README](https://github.com/matiassingers/awesome-readme)
* [Hackathon Starter](https://github.com/sahat/hackathon-starter)
* [Megaboilerplate](https://github.com/sahat/megaboilerplate)

Project Funding
* [Lemonade Stand](https://github.com/nayafia/lemonade-stand)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

<!--
Issue triage

https://github.com/blog/2097-improved-commenting-with-markdown

http://jlord.us/git-it
https://github.com/github/training-kit
https://github.com/github/teach.github.com
https://github.com/github-archive
https://github.com/github-archive/training.github.com


http://slides.com/kentcdodds/1st-pr#/
* [First Timers Only](https://medium.com/@kentcdodds/first-timers-only-78281ea47455#.barzl7cwa) 

https://gist.github.com/PurpleBooth/b24679402957c63ec426

http://hackforchange.org/tips-for-better-open-source-documentation
https://github.com/zalando/zalando-howto-open-source
https://github.com/ddbeck/readme-checklist

CODE_OF_CONDUCT
https://github.com/stevemao/github-issue-templates

https://github.com/devspace/awesome-github-templates
https://github.com/jessicard/remote-jobs/blob/master/PULL_REQUEST_TEMPLATE.MD
https://github.com/tylucaskelley/github-templates/blob/master/CONTRIBUTING.md

https://github.com/angular-translate/angular-translate/blob/master/CONTRIBUTING.md

https://github.com/jdorfman/awesome-help-wanted

https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md


Open Source Management, Codes of Conduct, Roadmaps
* [Open Source Management at Docker](https://github.com/docker/opensource)
* [Sentry Open Source Hosting](https://getsentry.com/for/open-source)

Example First-Timers Info
* [Pinax First-Timer Opportunity via Twitter](https://twitter.com/pinaxproject/status/687318459072446466) and [First-Timer](https://twitter.com/pinaxproject/status/694213861327659008)
* [How to Contribute to Pinax Blog Post](http://pinaxproject.com/pinax/ways_to_contribute) and [How to Contribute to Pinax Blog Post](http://blog.pinaxproject.com/2015/11/10/guide-how-contribute-pinax)
* [Pinax First Timers Only](http://blog.pinaxproject.com/2016/01/11/first-timers-only-and-new-labels), and [Pinax Issues GitHub](https://github.com/pinax/pinax/issues)
* [Pinax 16.04](http://blog.pinaxproject.com/2016/02/01/pinax-1604) and [Proposal for Pinax Distribution Versioning GitHub](https://github.com/pinax/pinax/issues/84)
* [Pinax Groupware Starter Project GitHub](https://github.com/pinax/pinax-starter-projects/wiki/Groupware-Starter-Project)

http://pinaxproject.com/pinax/how_to_contribute
https://docs.google.com/document/d/1f9hPTw3nelWy7nxaDawWP7EUl4QyeGeC4BNYeb4iWhU/edit
http://blog.pinaxproject.com/2016/04/25/pinax-developer-profiles-shosh-seiden/
http://blog.pinaxproject.com/2016/03/15/writing-better-documentation-and-why-documentation/
https://www.youtube.com/channel/UCAPpNG85GLzUBwzYCjd4raQ
https://plus.google.com/events/ca9n7iklbra4i67te8uh55468n0

https://github.com/pybee/voc/wiki/Your-first-VOC-contribution

https://medium.com/@kentcdodds/what-open-source-project-should-i-contribute-to-7d50ecfe1cb4#.sdw2t63pw

Start contributing to open source
* Do a GitHub search such as ["pull requests welcome"](https://github.com/search?utf8=%E2%9C%93&q=pull+requests+welcome)
https://github.com/search?utf8=%E2%9C%93&q=help+wanted
https://github.com/search?p=4&q=label%3A%22beginner%22&ref=searchresults&state=open&type=Issues&utf8=✓
https://github.com/search?utf8=✓&q=label%3A%22help+wanted%22&type=Issues&ref=searchresults
https://github.com/search?l=Ruby&q=label%3A%22help+wanted%22&ref=searchresults&type=Issues&utf8=✓

* [Jekyll Code of Conduct GitHub](https://github.com/jekyll/jekyll/blob/master/CONDUCT.md)
* [Rails Code of Conduct GitHub](https://github.com/rails/rails/blob/master/CODE_OF_CONDUCT.md)
https://github.com/HackathonHackers/code-of-conduct

Learn X in Y Minutes
* [Learn X in Y Minutes Git](https://learnxinyminutes.com/docs/git)
* [Learn X in Y Minutes Markdown](https://learnxinyminutes.com/docs/markdown) 

https://github.com/jlord/git-it

* [Git Index](http://gitref.org)  
* [Stanford Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic) 

Recommended
https://www.git-tower.com

https://git-scm.com/book/en/Git-Basics-Tips-and-Tricks

* [Enterprise Markdown Cheat Sheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
--> 
