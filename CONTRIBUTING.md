# Contributing Guidelines

We love improvements to our tools! There are a few key ways you can help us improve our projects:

## Discussing Possibilities for Data Together

We are engaging in a collaborative discussion about project aims and goals, the best place to join in is on [github.com/datatogether/](https://github.com/datatogether/) and all are welcome to join [our Slack chat](https://archivers-slack.herokuapp.com/).

## Submitting Feedback, Requests, and Bugs

Submitting feedback or feature requests and reporting bugs usually begins by
opening a [GitHub issues](https://help.github.com/articles/about-issues/)

Almost all repositories have their own set of issues:

        https://github.com/datatogether/<repository-name>/issues

Some projects have additional templates or sets of questions for each issue, which you will be prompted to fill out when creating one.

## Submitting Code and Documentation Changes

We have [project guidelines](https://github.com/datatogether/roadmap/PROJECT.md)
for all of the projects hosted in our
[GitHub Organization](https://github.com/datatogether), which all repositories
should follow.

Our process for accepting changes operates by
[Pull Request (PR)](https://help.github.com/articles/about-pull-requests/) and
has a few steps:

1.  If you haven't submitted anything before, and you aren't (yet!) a member of
our organization, **fork and clone** the repo:

        $ git clone git@github.com:<your-username>/<repository-name>.git

    Organization members should clone the upsteam repo, instead of working from
    a personal fork:

        $ git clone git@github.com:datatogether/<repository-name>.git

1.  Create a **new branch** for the changes you want to work on. Choose a topic
for your branch name that reflects the change:

        $ git checkout -b <branch-name>

1.  **Create or modify the files** with your changes. If you want to show other
people work that isn't ready to merge in, commit your changes then create a pull
request (PR) with _WIP_ or _Work In Progress_ in the title.

        https://github.com/datatogether/<repository-name>/pull/new/master

1.  Once your changes are ready for final review, commit your changes then
modify or **create your pull request (PR)**. Next, assign an active lead as a
reviewer or ping them (using "`@<username>`")

1.  Allow others sufficient **time for review and comments** before pinging
again. We make use of GitHub's review feature to comment in-line on PRs when
possible. There may be some fixes or adjustments you'll have to make based on
feedback.

1.  Once you have integrated comments, or waited for feedback, a lead should
merge your changes in!

_These guidelines are based on
[EDGI](https://github.com/edgi-govdata-archiving/) and
[Toronto Mesh](https://github.com/tomeshnet)'s._
