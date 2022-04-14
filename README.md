# collaboration-standards
This repo is a place for developing collaboration standards for the members of Data Innovation Lab

# How we use GitHub

## Start public

We value social impact. One way to achieve this goal is by making our codebase public. To do so, we start our GitHub repositories public whenever we can.

## No direct commits to the main branch—use pull requests instead

Our most up-to-date code lives on the main branch. We want to keep the main branch as bug-free as possible. To do so we want to avoid directly committing to the main branch. Direct commits to the main branch obscures the purpose of changes and ultimately hinders collaboration.

When starting a brand-new repository, you can protect the main branch in the repository's settings ([GitHub Docs]( https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches)). It's also a good practice to check "Include administrators" so that admins also cannot accidentally make direct commits.

## Branching

Include your name, and an issue number to the branch name. Separate your name with a slash `/`. (e.g., `nami/10-fix-dropdown`)
Create one branch for each feature/fix that you are working on. If the work is too big, consider breaking it down into small pieces, and creating a branch for each.

## Committing 

Commit often and commit early. A good commit will generally look like the following:

1. The commit message starts with an active verb (e.g., "Add a hierarchical model")
2. The chunks of commits do one thing

If you are having a hard time thinking about a concise commit message, your may be too complex. Try breaking it down to multiple commits.

## Pull requests

A good pull request describes what it does in a human-friendly language in both its title and description.
Avoid submitting a pull request without a description.

1. The title starts with an active verb (e.g., "Add a geolocation routine to the address lookup")
2. The reasons why you are making the changes
3. A link to the GitHub issue that you are addressing with a pull request
4. Details of making changes, so that others can understand what you did. Screenshots are also great tools to convey information. 

Tips: You can mention an issue that you are fixing, and use a keyword to fix the issue when the pull request is closed. ([GitHub Docs][1])


[1]: https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue
