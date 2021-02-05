# Git Resources

Focus on GitHub for now, not necessarily Git...

## Links

### GitHub
- [ ] **[GitHub Learning Lab](https://lab.github.com/)**
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
		
		1. Turn on GitHub Pages
		1. Close an issue
		1. Create a branch
		1. Commit a file
		1. Open a pull request
		1. Respond to a review
		1. Merge your pull request

		projects used:  
		[reveal.js](https://github.com/hakimel/reveal.js): a framework for creating presentations using HTML  
		[Jekyll](https://github.com/jekyll/jekyll): a simple, blog-aware, static site generator  
		
	1. [Git Handbook](https://guides.github.com/introduction/git-handbook/)
	
	1. Communicating using Markdown
	
	1. Uploading your project to GitHub
	- [ ] [First Week on GitHub](https://lab.github.com/githubtraining/first-week-on-github)

- [ ] **[GitHub Guides](https://guides.github.com/)**
	- [x] [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)  
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
	- [ ] [Git Handbook](https://guides.github.com/introduction/git-handbook/): part of 'First Day on GitHub' learning path
	- [ ] [Forking Projects](https://guides.github.com/activities/forking/)
	- [ ] [Be Social](https://guides.github.com/activities/socialize/)
	- [ ] [Making Your Code Citable](https://guides.github.com/activities/citable-code/)
	- [ ] [Mastering Issues](https://guides.github.com/features/issues/)
	- [x] [Mastering Markdown](https://guides.github.com/features/mastering-markdown/): completed under Markdown directory
	- [ ] [Documenting your projects on GitHub](https://guides.github.com/features/wikis/)

- [ ] [GitHub YouTube Channel](https://www.youtube.com/channel/UC7c3Kb6jYCRj4JOHHZTxKsQ)

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
- [ ] https://learngitbranching.js.org/

---

## Books

- [ ] *Git Community Book (PDF)*
- [ ] *[Pro Git](https://git-scm.com/book/en/v2) (and PDF)*
- [ ] *[20 free PDF books!](https://www.ubuntupit.com/best-git-books-for-newbie-and-professional-programmers/)*
