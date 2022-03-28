# collaboration-standards
This repo is a place for developing collaboration standards across the members of Data Innovation Lab

# How we use GitHub

## Start public

We value social impact. One way to achieve this goal is making our codebase public. To do so, we start our repos public as much as possible.

## No direct commits to the main branch—use pull requests instead

Our most up-to-date code lives on the main branch. We want to keep the main branch as bug-free as possible. To do so we want to avoid directly commiting to the main branch. Direct commits to the main branch obscures the purpose of changes and ultimately hinders collaboration.

When starting a brand-new repository, you can protect the main branch in the repository's settings ([doc]( https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches)). It's also a good practice to check "Include administrators" so that admins also cannot accidentally make direct commits.

## Use unique branch names

When making changes, you want to be working on your unique branch and feature/fix. (e.g., `nami/10-fix-dropdown`)
Create one branch for each feature/fix that you are working on. If the work is too big, consider braking it down to small pieces.

## Commiting 

We want to commit often and commit ealy. A good commit will generally look like the following:

1. The commit message starts with an active verb (e.g., "Add a hierarchical model")
2. The chunks of commits do one thing

If you struggle to think about a clear commit message, it may be that the changes are doing complex things. Try breaking it down to multiple commits.

## Formatting pull requests

A good pull request describes what it does in a human-friendly language. A rule of thumb, it inclues the following:

1. The title starts with an active verb (e.g., "Add a geolocation routine to the address lookup")
2. The rasons why you are making the changes
3. A link to the GitHub issue that you are addressing with a pull request
4. Details of making changes, so that others can understand what you did. Screenshots are also great tools to convey information. 

