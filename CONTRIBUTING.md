# Contributing to Circles

## :sloth: Styleguide

### Commit Messages

* Capitalize the first line and each paragraph
* Use present tense (*"Add feature ..."* instead of *"Added feature ..."*)
* Use the imperative mood (*"Move cursor to ..."* instead of *"Moves cursor to ..."*)
* Limit the first line to 72 characters or less
* Do not end the subject line with a period
* Use the body to explain what and why you have done something, refer to issues and PRs if you want

Check out the [guidelines for commit messages](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53) for more examples and recommendations.

### Branches

* `main` contains only reviewed, tested and released code
* You can not push directly to `main`, create a branch with your changes and open a PR to request code review before merging
* Follow simple branch naming scheme clearly describing the topic (e.g., `refactor-authentication`, `make-retina-avatars`)

### Pull Requests

* Use the description field to describe what you are introducing or changing in your branch
* You can [add TODO lists](https://docs.github.com/en/github/managing-your-work-on-github/about-task-lists) in the description field
* Mention related issues in the description field by writing `Closes #<issue no>`. This will [automatically close the issue](https://github.blog/2013-01-22-closing-issues-via-commit-messages/) when your contribution got merged
* Change the PR to ["Draft" state](https://github.blog/2019-02-14-introducing-draft-pull-requests/) if your work is not done yet
* Click "Ready to Review" to request merging your branch into `main`
