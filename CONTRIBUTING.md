# Contributing to Circles

## :sloth: Styleguide

### Code

* All repositories have linters in place which help you to follow the recommended style guidelines for formatting code. Read in the according `README.md` of the repository to find out how to run the linter tasks.

### Commit Messages

* Capitalize the first line and each paragraph
* Use present tense (*"Add feature ..."* instead of *"Added feature ..."*)
* Use the imperative mood (*"Move cursor to ..."* instead of *"Moves cursor to ..."*)
* Limit the first line to 72 characters or less
* Do not end the subject line with a period
* Use the body to explain what and why you have done something, refer to issues and PRs if you want

Check out the [guidelines for commit messages](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53) for more examples and recommendations.

### Branches

* Follow a simple naming scheme clearly describing the topic (e.g., `refactor-authentication`, `make-retina-avatars`) you are working on

### Pull Requests

* Use the description field to describe what you are introducing or changing in your branch
* You can [add TODO lists](https://docs.github.com/en/github/managing-your-work-on-github/about-task-lists) in the description field
* Mention related issues in the description field by writing `Closes #<issue no>`. This will [automatically close the issue](https://github.blog/2013-01-22-closing-issues-via-commit-messages/) when your contribution got merged

## :turtle: How to ..

### Merge branches

* You can not push directly to `main`, please create a branch with your changes and open a PR to request code review before merging
* Change the PR to ["Draft" state](https://github.blog/2019-02-14-introducing-draft-pull-requests/) if your work is not done yet
* Make sure you followed the [Styleguide](#Styleguide) and linter recommendations
* Verify that all status checks are passing
* Click "Ready to Review" to request merging your branch into `main`
* Merges require the approval of at least one core maintainer. The reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be finally accepted

### Release new versions

* All releases follow the [semantic versioning scheme](https://semver.org/)
* The `main` branch should contain only tested, reviewed and released code
* `staging` branch should contain code that is compiled and run on the Circles staging servers
* Release additions, updates, fixes and breaking changes are always documented in `CHANGELOG.md` following this [scheme](https://keepachangelog.com)
* Release commits are tagged via git and additionally maintained as GitHub releases
