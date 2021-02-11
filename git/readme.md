# Git and GitHub resources

---

*Focus on GitHub for now, not necessarily Git...*  

## Projects / use cases

- [ ] make repos for my various projects (baseball, fantasy football, educational tracking, etc.)
- [ ] create presentations using [reveal.js](https://revealjs.com/) - see my [github-slideshow repo](https://github.com/adilw893/github-slideshow)
- [ ] create website via [GitHub Pages](https://pages.github.com/) / [Jekyll][jek]

---

## Links

### [GitHub](https://github.com)

#### [GitHub Learning Lab](https://lab.github.com/)

- [ ] **[First Day on GitHub](https://lab.github.com/githubtraining/first-day-on-github)**

1. [What is GitHub?](https://youtu.be/w3jLJU7DT5E)  
platform that helps people build software by working together  
*branches* to the code create an 'alternate timeline' where you can make changes to the code without disrupting the current existing software  
GitHub tracks changes (*commits*) and saves snapshots of progress  
once you're ready to collaborate with the rest of the team, open a *pull request* to share the changes you're proposing, then review and discuss them  
then once everybody has signed off on the changes, the new code can be incorporated into the project by *merging* the pull request into the `main` branch  
as soon as it is merged, it is immediately available to all users  

1. [Introduction to GitHub](https://lab.github.com/githubtraining/introduction-to-github)  

  1. Assign yourself  
GitHub is a **collaboration platform** and a **version control** tool  
[Git](https://docs.github.com/en/github/getting-started-with-github/github-glossary#git) is the most popular open source version control software, tracks every contribution and contributor to your project  
**Git** is an open source program for tracking changes in text files, written by the author of the Linux OS  
**GitHub** is a social and user interface built on top of Git  
[Exploring a Repository](https://www.youtube.com/watch?v=R8OAwrcMlRw)  
a *repository* is the container that holds everything related to your project  
the code view shows all files in the repository, it is also called the *root* of the project  
all repositories should contain a *readme* file, and it will automatically be displayed below the repository  
*issues* are used to track bugs and feature requests, they can be assigned to team members, and are designed to encourage discussion and collaboration  
a *pull request* represents a change the author would like to make to the repository, and they are used to resolve issues  
more repository features:  
  * Project boards: Kanban-style task tracking  
  * Wiki: create and store relevant project documentation  
  * Insights: analytics tools for your repository such as Pulse (project dashboard) and Graphs (granular view of repository activity)  
other special files (besides README.md):  
  * CONTRIBUTING.md: used to describe the process for contributing to the repository, a link to this is shown anytime someone creates a new issue or pull request  
  * ISSUE_TEMPLATE.md: another file you can use to pre-populate the body of an issue, every new issue will be opened with this starter text  
[Using Issues](https://docs.github.com/en/github/getting-started-with-github/github-glossary#issue)  
an [issue](https://docs.github.com/en/github/getting-started-with-github/github-glossary#issue) is a place where you can have a conversation about ideas, bugs, code review, suggested improvements, tasks, questions, and anything else  
they can be categorized with labels and assigned to specific people  
think of an issue title as an email subject line  
they provide the entire background story in one place  
they can be cross-linked to other issues or pull requests  
create a single, comprehensive record of how/why decisions were made  
allow you to easily pull in specific people with @-mentions  
support Markdown formatting, and the 'Preview' tab shows how it will be rendered  
[Watching, notifications, stars, and explore](https://www.youtube.com/watch?v=ocQldxF7fMY)  
*watching* a repository allows you to stay up-to-date on what is happening within that project  
once you comment on an issue or pull request, you will start to receive email notifications whenever there is activity in the thread  
under each issue / pull request, go to 'Notifications' to subscribe or unsubscribe from notifications  
you can also customize your global notification settings under your Profile > Settings > Notifications  
that is where you can opt to receive notifications via email or the web interface  
  * Watch: you'll receive all notifications (new issues, pull requests, or comments, issues closed, pull requests merged)  
  * Not watching: won't receive notifications unless you're @-mentioned  
  * Ignore: won't receive any notifications  
*starring* a repository adds it a list of favorites (think bookmarks), you won't get notifications  
under Profile > *Explore*, you can see the full range of what GitHub has to offer and find new projects  

  1. Turn on [GitHub Pages](https://pages.github.com/)  
GitHub Pages allow you to serve a static site from a repository
Settings > GitHub Pages > change 'Source' dropdown to `main` branch and save
can also apply themes at this point

  1. Close an issue  
the site is now visible to the public at <https://adilw893.github.io/github-slideshow/>
since tasks in the issue have been completed, now you can close the issue (with the 'Close issue' button)

  1. Create a branch  
The [GitHub Flow](https://www.youtube.com/watch?v=PBI2Rz-ZOxU)  
create a branch off of the `master` or `main` (canonical) branch  
a *branch* is a parallel version of a repository, separating your work and allowing you to work freely without disrupting the 'live' version  
your new branch (a 'feature' branch) will look exactly like `master` at first, but then any changes you make will only be reflected in this branch  
when you make file changes, you'll commit those files to the feature branch  
then open a *pull request* for your branch (a request to merge), allowing for discussion and review  
think of the pull request as a starting point, not necessarily a finished product  
when ready and changes are approved, the feature branch can be merged into the master branch  
*merging* takes changes from one branch (feature) and applies them to another (`main`)
to keep branches organized, keep them concise and short-lived (i.e., focus on only a single feature or bug fix)  

  1. Commit a file  

when finished creating or editing a file, then you can *commit* the file  
use a commit message to briefly indicate the changes  
commit message best practices:
* don't end it with a period
* keep it brief (you can use the extended description box for more detail if necessary)
* use active voice (e.g., 'add' instead of 'added')

  1. Open a pull request  

once you've made a commit (or more), you can share your proposed changes with a *pull request*  
issues encourage discussion and collaboration, whereas pull requests help share changes, deliver feedback, and iterate until approval  
[Creating Pull Requests](https://www.youtube.com/watch?v=kJr-PIfLDl4&feature=youtu.be)  
a pull request introduces an action that addresses an issue  
it is considered a work in progress until it is merged into the project  
add commentary explaining why you're proposing the changes and reference specific issues with the `#` sign  
the *diff* view shows file changes (red indicates removals, green indicates additions)  
if something needs to be changed in the *diff* view, click on a line number to add a *line comment*  
you can also add more general comments to the conversation like in issues  
pull requests typically require sign-off from someone before merging into the main branch  
when creating a new pull request, make sure the `base` and `compare` branches are selected appropriately in the dropdown menus  

  1. Respond to a review  

review the 'Files Changed' tab to see the diffs  
from there you can navigate to edit files and then make new commits  

  1. Merge your pull request  

once the pull request has successfully passed review, merge the pull request  
and since the branch has been merged, it is no longer needed and should be deleted  



projects used:  
[reveal.js](https://github.com/hakimel/reveal.js): a framework for creating presentations using HTML  
[Jekyll](https://github.com/jekyll/jekyll): a simple, blog-aware, static site generator  

1. [Git Handbook](https://guides.github.com/introduction/git-handbook/)  

VCS = version control system  
a VCS tracks the history of changes as people and teams collaborate on projects together  
any version of the project can be recovered at any time  
review the project history to see which changes were made, by whom, when, and why  
a distributed VCS (DVCS) allows every user access to a full and self-contained history of all changes  
rather than a centralized VCS, a DVCS doesn't need a constant connection to a central repository, and developers can collaborate remotely and asynchronously  
a VCS gives each contributor a unified and consistent view of the project, allowing team members to stay aligned while working independently  
[Git](https://git-scm.com/) is the most used VCS in the world  
* Git lets developers see the entire timeline of any project in one place, providing important context right away
* Collaboration can happen at any time while maintaining source code integrity
* Can help break down communication barriers among teams
a Git project is a *repository*  
a repository encompasses the entire collection of files and folders associated with a project, along with each file's revision history  
the file history is made of snapshots in time called *commits*  
developers are encouraged to fix bugs or add new features without fear of derailing mainline development efforts  
this is achieved through *branches*, lightweight pointers to historical commits that can be easily created and deprecated when no longer needed  
Git commands can be executed from the command line or via an application like GitHub Desktop  
* `git init` initializes a brand new Git repository and begins tracking an existing directory
* `git clone` creates a local copy of a project that already exists remotely (all files, history, and branches)
* `git add` stage changes that will become part of the next snapshot/commit (first part of two-step process to track changes)
* `git commit` saves snapshot to the project's history (second part of two-step process to track changes)
* `git status` shows the status of changes as untracked, modified, or staged
* `git branch` shows the branches being worked on locally
* `git merge` merges lines of development together (typically used to combine changes made on two distinct branches)
* `git pull` updates the local line of development with updates from its remote counterpart
* `git push` updates the remote repository with any commits made locally to a branch
[full reference guide to Git commands](https://git-scm.com/docs)  
GitHub flow = developers create a branch to work on updates, commit changes to save them, open a pull request to propose and discuss them, and merge pull requests once everyone is on the same page  
* create a branch - short-lived topic branches keep teams focused and results in quick ships
* add commits - snapshots create safe, revertible points in the project's history
* open a pull request - publicize ongoing efforts and allow for a transparent development process
* discuss and review code - comment, test, and review open pull requests
* merge - merges a feature branch into the main branch
* deploy
**skipped over GitHub command line examples**  
there are two primary ways people collaborate on GitHub:  
  1. shared repository
  1. fork and pull
  with a *shared repository*, individuals and teams are explicitly designated as contirubtors with read, write, or administrator access  
  a *fork* is a copy of a project under a developer's own personal account, and all work is kept separate from the original project  
  then work in a fork can be surface back to the original project via a pull request, and maintainers can review and merge the suggested changes  

1. Communicating using Markdown  



1. Uploading your project to GitHub  

- [ ] [First Week on GitHub](https://lab.github.com/githubtraining/first-week-on-github)

#### [GitHub Guides](https://guides.github.com/)

- [x] [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/) completed 2/5/21  
  lightweight, branch-based workflow where deployments are made regularly  

  1. create a *branch*  
  branching helps manage different features and ideas that are in progress simultaneously  
  changes you make in a branch won't affect the `main` branch, so you can experiment  
  then branches can be merged into the `main` branch once they are complete and have been reviewed  
  the only rule regarding branching: **anything in the `main` branch is deployable**  
  make sure that you branch off of `main` (not other branches)  
  also, descriptive branch names will help show what you're working on  

  1. add *commits*  
  once a branch has been created, start making changes  
  whenever you add, edit, or delete a file, you're making a commit  
  adding commits to a branch helps keep track of progress and creates a transparent history  
  each commit is a separate unit of change  
  you can roll back commits via the history if necessary  
  **use commit messages to explain why the changes were made**  

  1. open a *pull request*  
  pull requests initiate discussion about your commits  
  can see exactly what changes would be merged if the request is accepted  
  use @-mentions in pull request messages/comments to specify certain individuals or teams  
  pull requests are useful for contributing to open-source projects  
  'Fork & Pull' model: pull requests notify project maintainers about changes you'd like them to consider  
  and pull requests are also used for managing changes to shared repositories  
  'Shared Repository' model: pull requests help start code review and discussion of proposed changes before merging into the `main` branch  

  1. discuss and review your code  
  pull requests encourage and capture questions and comments, e.g., missing unit tests or 'LGTM'  
  you can continue to make changes and push commits to a branch while the pull request is open, addressing feedback  
  pull requests support Markdown formatting  

  1. *deploy*  
  once the pull request has been reviewed, you can deploy changes from a branch for final testing in production before merging to `main`  
  if it causes issues, you can roll back by deploying the existing `main` branch into production  

  1. *merge*  
  once changes have been verified in production, the code can be merged into the `main` branch  
  once merged, the pull requests preserve a record of historical changes to the code  
  by incorporating certain keywords into the pull request, you can associate issues with the code  
  then merging the pull request would close the issue  

- [ ] **[Hello World](https://guides.github.com/activities/hello-world/)**
- [ ] [Getting Started with GitHub Pages](https://guides.github.com/features/pages/)
- [x] [Git Handbook](https://guides.github.com/introduction/git-handbook/): part of 'First Day on GitHub' learning path
- [x] [Forking Projects](https://guides.github.com/activities/forking/)

when you want to contribute to someone else's project, or leverage their project as a starting point for your own  
a *fork* is a personal copy of someone else's project  
you can submit pull requests to offer your changes up to the original project ('social coding')  
click the **Fork** button in the repository header (by **Watch** and **Star**)  
clone it to your computer by hitting the clone/download button and open in GitHub Desktop  
make changes to the project files by using a text editor (like [Atom](https://atom.io/))  
when ready to submit, *stage* and *commit* your changes, then *push* them to the remote  
after pushing, navigate to the repository on <github.com>, and it will indicate you can compare and submit a pull request to the original project  
add a title and description providing the rationale behind your pull request, and then it's up to the maintainer if they would like to implement or not  

- [ ] [Be Social](https://guides.github.com/activities/socialize/)
- [ ] [Making Your Code Citable](https://guides.github.com/activities/citable-code/)
- [ ] [Mastering Issues](https://guides.github.com/features/issues/)
- [x] [Mastering Markdown](https://guides.github.com/features/mastering-markdown/): completed under Markdown directory
- [ ] [Documenting your projects on GitHub](https://guides.github.com/features/wikis/)

- [ ] [GitHub YouTube Channel](https://www.youtube.com/channel/UC7c3Kb6jYCRj4JOHHZTxKsQ)
- [ ] [GitHub YouTube Training & Guides](https://www.youtube.com/githubguides)

### Other
- [ ] https://www.edureka.co/blog/git-tutorial/
- [ ] https://www.youtube.com/watch?v=xuB1Id2Wxak

---

## Courses

### Coursera
- [ ] https://www.coursera.org/learn/introduction-git-github
- [ ] https://www.coursera.org/learn/version-control-with-git
- [ ] https://www.coursera.org/learn/git-distributed-development
- [ ] https://www.coursera.org/projects/git-and-github
- [ ] https://www.coursera.org/projects/git-for-developers-using-github

### Udacity
- [ ] https://www.udacity.com/course/version-control-with-git--ud123

### Codecademy
- [ ] https://www.codecademy.com/learn/learn-git

### Datacamp
- [ ] https://www.datacamp.com/courses/introduction-to-git

### LinkedIn Learning
- [ ] https://www.linkedin.com/learning/github-for-data-scientists
- [ ] https://www.linkedin.com/learning/github-quick-tips

### Udemy
- [ ] https://www.udemy.com/course/git-started-with-github/
- [ ] https://www.udemy.com/course/git-and-github-crash-course-creating-a-repository-from-scratch/
- [ ] https://www.udemy.com/course/git-expert-4-hours/
- [ ] https://www.udemy.com/course/learngit/
- [ ] https://www.udemy.com/course/intro-to-git/
- [ ] https://www.udemy.com/course/the-ultimate-git-5-day-challenge/

### Other
- [ ] [Git](https://git-scm.com/)
- [ ] [Git Reference Documents](https://git-scm.com/docs)
- [ ] https://learngitbranching.js.org/

---

## Books

- [ ] *Git Community Book (PDF)*
- [ ] *[Pro Git](https://git-scm.com/book/en/v2) (and PDF)*
- [ ] *[20 free PDF books!](https://www.ubuntupit.com/best-git-books-for-newbie-and-professional-programmers/)*
