
# Code Reviews

All code is reviewed before merging into a development or master branch.

Background: we use the [Git Flow](https://nvie.com/posts/a-successful-git-branching-model/) methodology for branches.  

## Code Review Steps

1.  You work on a **feature** or **hotfix** branch.  When you are ready to merge your code into the **develop** or **master** branch, you commit and push your branch to github.
2.  Go to github.com at the root of the repository and you should see a green section with a button to create a pull request.
3.  Create the PR.  Assign the reviewer of choice to the PR.  If the branch is related to a ticket in a task management system, be sure to include a link to that task for the reviewer.
4.  The reviewer should check out the branch, compile or run it, and ensure that it behaves as expected.
5.  The reviewer approves the PR and merges it.
6.  The reviewer then changes the task status in the task management system if applicable.

## For the Developer Being Reviewed

* Expect pickiness.  It's part of our culture.  We care about details.
* If the reviewer suggests something that you disagree with, take time to understand where it's coming from.  
* Ask a third developer for their opinion.

## For the Reviewer

* Being picky is a good thing.
* Commenting on style and suggesting ways to make the code more elegant is great.
* We care about whitespace, typos, and code style.  This is part of being a considerate developer who cares about the long term maintainability of code.
* Ask a third developer if you get into a disagreement with the developer.