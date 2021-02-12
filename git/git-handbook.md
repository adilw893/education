part of the [First Day on GitHub](https://lab.github.com/githubtraining/first-day-on-github) learning path of the GitHub [Learning Lab](https://lab.github.com/)  

---

# [Git Handbook](https://guides.github.com/introduction/git-handbook/)  

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
