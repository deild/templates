# Contributing Guide

Welcome! We love receiving contributions from our community, so thanks for stopping by! There are many ways to contribute, including submitting bug reports, improving documentation, submitting feature requests, reviewing new submissions, or contributing code that can be incorporated into the project.

This document describes our development process. Following these guidelines shows that you respect the time and effort of the developers managing this project. In return, you will be shown respect in addressing your issue, reviewing your changes, and incorporating your contributions.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct][0]. We expect all contributors to follow the [Code of Conduct][0] and to treat fellow humans with respect.

## Reporting Bugs

**If you find a security vulnerability, do NOT open an issue. Email EMAIL@DOMAIN.COM instead.**

Before you submit your issue, please [search the issue archive][6] - maybe your question or issue has already been identified or addressed.

If you find a bug in the source code, you can help us by [submitting an issue to our GitHub issue tracker][6]. Even better, you can submit a Pull Request with a fix.

## Contributing Code

Working on your first open source project or pull request? Her are some helpful tutorials:

* [How to Contribute to an Open Source Project on GitHub][2]
* [Make a Pull Request][3]
* [First Timers Only][4]

### Getting Started

Install these dependencies:

```
with some examples
```

You will need to fork the main repository to work on your changes. Simply navigate to our GitHub page and click the "Fork" button at the top. Once you've forked the repository, you can clone your new repository and start making edits.

In git it is best to isolate each topic or feature into a “topic branch”. While individual commits allow you control over how small individual changes are made to the code, branches are a great way to group a set of commits all related to one feature together, or to isolate different efforts when you might be working on multiple topics at the same time.

While it takes some experience to get the right feel about how to break up commits, a topic branch should be limited in scope to a single issue

```
# Checkout the master branch - you want your new branch to come from master
git checkout master

# Create a new branch named newfeature (give your branch its own simple informative name)
git branch newfeature

# Switch to your new branch
git checkout newfeature
```

For more information on the GitHub fork and pull-request processes, [please see this helpful guide][5].

### Development Process

This project follows the [git flow](http://nvie.com/posts/a-successful-git-branching-model/) branching model of product development.

You should be using the master branch for the most stable release; please review [release notes][1] regularly. If you want to keep up with the latest changes, we work in the `dev` branch.

### Building the Project

What branches should be work be started off of?

Include instructions on how to build the project.

```
make build
```

Provide instructions on adding a new file/module to the build

```
with some examples
```

Keep your tests as simple as possible.

### Testing

If you add code you need to add tests! We’ve learned the hard way that code without tests is undependable. If your pull request reduces our test coverage because it lacks tests then it will be rejected.

Provide instructions for adding new tests. Provide instructions for running tests.

```
with examples
```

### Git Commit Guidelines

The first line of the commit log must be treated as as an email subject line.
It must be strictly no greater than 50 characters long.
The subject must stand on its own and not only make external references such
as to relevant bug numbers.

The second line must be blank.

The third line begins the body of the commit message (one or more paragraphs)
describing the details of the commit.
Paragraphs are each separated by a blank line.
Paragraphs must be word wrapped to be no longer than 76 characters.

The last part of the commit log should contain all "external
references", such as which issues were fixed.

For further notes about git commit messages, [please read this blog post][7].

[0]: CODE_OF_CONDUCT.md
[1]: https://github.com/your/project/releases
[2]: https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github
[3]: http://makeapullrequest.com/
[4]: http://www.firsttimersonly.com
[5]: https://gist.github.com/Chaser324/ce0505fbed06b947d962
[6]: https://github.com/your/project/issues
[7]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
