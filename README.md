# Setting Up An Open Source Project

## Open Source Project Documentation

### README.md

<!--
* [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown) 
https://guides.github.com/features/mastering-markdown
-->

* Badges
* Project explanation
* Installation guidance
* Credit to contributors

Set up wiki when README too big
* settings/options, other option -> Restrict editing to collaborators only
* GitHub wikis use GitHub flavored markdown
* Link across pages using page name as anchor
* Badges

Fantastic README Examples
* [Hackathon Starter](https://github.com/sahat/hackathon-starter)
* [Megaboilerplate](https://github.com/sahat/megaboilerplate)

### LICENSE.md

* [GitHub Choose a License](http://choosealicense.com)
* [GitHub Open Source Licensing](https://help.github.com/articles/open-source-licensing) 

### .gitignore

* [Git Ignore GitHub](https://github.com/github/gitignore) 
 
### CODE_OF_CONDUCT.md

* [Adding a Code of Conduct to Your Project](https://help.github.com/articles/adding-a-code-of-conduct-to-your-project)

### CONTRIBUTING.md

* [Setting Guidelines for Repository Contributors](https://help.github.com/articles/setting-guidelines-for-repository-contributors)

Types of Info Included
* Installation guidance

### Styleguide

### Templates

<!--
https://github.com/blog/2111-issue-and-pull-request-templates
-->

#### ISSUES_TEMPLATES.md

<!--
https://help.github.com/articles/creating-an-issue-template-for-your-repository
https://help.github.com/articles/creating-a-pull-request-template-for-your-repository
-->

* Issues Guidance

#### PULL_REQUESTS_TEMPLATES.md

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

* [See All Contributors Emoji Key for Role Examples](https://github.com/kentcdodds/all-contributors#emoji-key)

A Few Common
* Writing code, maintaining code
* Accepting pull requests
* Writing documentation
* Answering questions

## New Contributors

Ideally, make project welcoming to newcomers, with user-friendly documentation

Helpful Info
* [Helping People Contribute to Your Project](https://help.github.com/articles/helping-people-contribute-to-your-project)

Mentors
* Include mentor list if applicable

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

## Other Helpful Resources
* [GitHub Blog](https://github.com/blog) 


<!--
* [GitHub Features (Code Review, ect.)](https://github.com/features)
https://guides.github.com/introduction/flow
https://help.github.com/articles/about-repository-graphs#traffic
https://help.github.com/articles/tracking-the-progress-of-your-work-with-projects

https://guides.github.com/features/issues
https://github.com/blog/957-introducing-issue-mentions

https://help.github.com/articles/creating-and-editing-milestones-for-issues-and-pull-requests
https://help.github.com/articles/associating-milestones-with-issues-and-pull-requests
https://github.com/blog/2178-multiple-assignees-on-issues-and-pull-requests

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

Start contributing to open source
* Do a GitHub search such as ["pull requests welcome"](https://github.com/search?utf8=%E2%9C%93&q=pull+requests+welcome)
https://github.com/search?utf8=%E2%9C%93&q=help+wanted
https://github.com/search?p=4&q=label%3A%22beginner%22&ref=searchresults&state=open&type=Issues&utf8=✓
https://github.com/search?utf8=✓&q=label%3A%22help+wanted%22&type=Issues&ref=searchresults
https://github.com/search?l=Ruby&q=label%3A%22help+wanted%22&ref=searchresults&type=Issues&utf8=✓

https://medium.com/@kentcdodds/what-open-source-project-should-i-contribute-to-7d50ecfe1cb4#.sdw2t63pw
https://github.com/jfmengels/all-contributors-cli

* [Jekyll Code of Conduct GitHub](https://github.com/jekyll/jekyll/blob/master/CONDUCT.md)
* [Rails Code of Conduct GitHub](https://github.com/rails/rails/blob/master/CODE_OF_CONDUCT.md)
https://github.com/HackathonHackers/code-of-conduct


#### Git and Markdown

Learn X in Y Minutes Git
* [Learn X in Y Minutes Git](https://learnxinyminutes.com/docs/git)

https://github.com/jlord/git-it

* [Git Index](http://gitref.org)  
* [Stanford Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic) 

Recommended
https://www.git-tower.com

https://git-scm.com/book/en/Git-Basics-Tips-and-Tricks

https://github.com/git-ftp
https://github.com/github/git-lfs
https://git-lfs.github.com

Markdown
* [Learn X in Y Minutes Markdown](https://learnxinyminutes.com/docs/markdown) 
* [Enterprise Markdown Cheat Sheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
--> 
