# Setting Up An Open Source Project

## Open Source Project Documentation

### README.md

Important Parts
* Badges
* Project explanation
* Installation guidance
* Credit to contributors

Set up wiki when README too big
* settings/options, other option -> Restrict editing to collaborators only
* GitHub wikis use GitHub flavored markdown
* Link across pages using page name as anchor
* Badges

### LICENSE.md
### .gitignore
### CODE_OF_CONDUCT.md
### CONTRIBUTING.md

Important Parts
* Installation guidance

### Styleguide
### ISSUES_TEMPLATES.md

* Issues Guidance

### PULL_REQUESTS_TEMPLATES.md

* Pull request Guidance

### CHANGELOG.md
### RELEASING.md

## Organizations

* [About GitHub Organizations](https://help.github.com/articles/about-organizations)

Repo Access
* Public repo- anyone can access
* Private repo- only collaborators

Access Control in GitHub
* Owners can do anything
* Collaborators have full read/write access (can push to the project, merge pull requests), but not administrative access (can't change settings, add new collaborators)
* If you want to restrict someone's access to commit to master branch, instead of adding them as a collaborator, ask them to fork the repo to make changes
* Have team members work on the same code base, but have separate repo that you send pull requests to that only your operations manager or team lead can accept

GitHub Organizations and Teams
* Organizations are for code owned by groups (for companies, OSS projects)
* Teams allow easier management of permissions (add a developer to a team, and then give team access to a number of repos)

## Issues

<!--
* Labels- Beginner friendly

Listing issues- issues tab, open/closed, filtering issues
Labels- example: features and bugs, including multiple labels
Assign, milestone, issue notifications, subscribe/unsubscribe to an issue
Respond by replying to any email about that issue

Issues- keyboard shortcuts
New issue, drop down list of developers, select/create new milestone
Rails repo issues- filter issues by milestone, labels
-->

Enable Issues to:
* Track bugs
* Manage features

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

## Roles

* Writing code, maintaining code
* Accepting pull requests
* Writing documentation
* Answering questions

## New Contributors

Ideally, make project welcoming to newcomers, with user-friendly documentation

Mentors
* Include mentor list if applicable

GitHub Documentation
* [Git Homepage](https://git-scm.com)
* [Set Up Git](https://help.github.com/articles/set-up-git)
* [GitHub Hello World Tutorial](https://guides.github.com/activities/hello-world)
* [GitHub Help](https://help.github.com)  
* [GitHub Training](http://training.github.com)  
* [GitHub Bootcamp](https://help.github.com/categories/bootcamp)  
* [GitHub Guides](https://guides.github.com) 
