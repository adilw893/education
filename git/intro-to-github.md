part of the [First Day on GitHub](https://lab.github.com/githubtraining/first-day-on-github) learning path of the GitHub [Learning Lab](https://lab.github.com/)  

---

# [Introduction to GitHub](https://lab.github.com/githubtraining/introduction-to-github)

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