one of the [GitHub Guides](https://guides.github.com/)

---

# [Understanding the GitHub Flow](./github-flow.md)

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
