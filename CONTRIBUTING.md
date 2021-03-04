# Contributing to Circles

## :goat: Welcome!

We are very excited to hear that you take your time to help building the Circles UBI project used by users and groups all around the world! :star: If you have an idea, suggestion or bugfix to improve Circles, please read these guidelines carefully and reach out for help in our channels when you have any questions.

## :monkey: Code of Conduct

> **Note:** Circles is a community project maintained by volunteers and people dedicated to it in various organizational forms. While we are working hard to improve the infrastructure, stability and code, please be respectful with the current contributors around this project which dedicate their limited time to make all of this work. :heart:

To create a safe environment for all contributors and members, Circles is governed by the [Circles Code of Conduct](https://github.com/CirclesUBI/.github/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please [report](https://github.com/CirclesUBI/.github/blob/main/CODE_OF_CONDUCT.md#reporting) unacceptable behavior to counsellor@bitspossessed.org.
  
## :tropical_fish: Join us, ask for help

We have an **official board and chat** where the community helps you if you have questions:

:arrow_right: [Official Circles chat @ RocketChat](https://chat.joincircles.net)

* Say hi and tell the others about yourself in our `#general` channel
* Check out the `#development` channel for technical questions

:arrow_right: [Official discussion forum for Circles @ Discourse](https://aboutcircles.com)

## :cow: Overview

If you are new to the Circles project and you need an overview of all components of the system and some development guidelines, **we recommend you to check out the following documents:**

* The official [Circles Handbook](https://handbook.joincircles.net/) gives you an **introduction into the Circles system architecture**, tutorials to deploy your own Circles server but also how to write and run Circles code locally on your computer
* The [Circles Whitepaper](https://handbook.joincircles.net/about/whitepaper.html) will give you a **good overview of how Circles actually works**
* Check out the [FAQ](https://joincircles.net/faq) on the Circles website

## :panda_face: How Can I Contribute?

Any sort of contribution is welcome! Here are some examples:

* Report a bug you identified
* Write code which enhances the system or fixes an issue
* Add a tutorial to the [`Circles Handbook`]
* Improve the documentation or installation steps for a service
* Translate the [`Circles Wallet`] or [`Website`] in another language

[`Circles Handbook`]: https://github.com/CirclesUBI/circles-handbook
[`Circles Wallet`]: https://github.com/CirclesUBI/circles-myxogastria/tree/main/locales
[`Website`]: https://github.com/CirclesUBI/circles-website/tree/master/public/static/locales

### Reporting Bugs

This section guides you through submitting a bug report for Circles. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer:, and find related reports :mag_right:.

Before creating bug reports, please check if the problem has already been mentioned in the regarding issues of the regarding GitHub repository. When you are creating a bug report, please include as many details as possible. Fill out the required [bug report template](https://github.com/CirclesUBI/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

### Suggesting new features

This section guides you through submitting an enhancement suggestion for Circles, including completely new features and minor improvements to existing functionality.

Before suggesting a new feature on GitHub you can introduce your ideas first to the Circles community by writing a post in the [Circles forum](https://aboutcircles.com). You might receive helpful feedback before implementing your idea. After you've determined which repository your enhancement suggestion is related to, create an issue on that repository using the [feature template](https://github.com/CirclesUBI/.github/blob/master/.github/ISSUE_TEMPLATE/feature_request.md).

### Your First Code Contribution

Unsure where to begin contributing to Circles? You can start by looking through these `good-first-issue` or `help-wanted` issues:

* [`good-first-issue`] - issues which should only require a few lines of code, and a test or two
* [`help-wanted`] - issues which should be a bit more involved than `good-first-issue` issues

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
* Release additions, updates, fixes and breaking changes are always documented in `CHANGELOG.md` following this [scheme](https://keepachangelog.com)
* Release commits are tagged via git and additionally maintained as GitHub releases

[`good-first-issue`]: https://github.com/search?l=&q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue+%3Aheart%3A%22+user%3ACirclesUBI+sort%3Acomments-desc&type=issues
[`help-wanted`]: https://github.com/search?l=&q=is%3Aopen+is%3Aissue+label%3A%22help+wanted+%3Aheart%3A%22+user%3ACirclesUBI+sort%3Acomments-desc&type=issues
