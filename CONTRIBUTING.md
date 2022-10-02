# Contributing

This document describes the contribution guideline for `medusa-whatsapp-business-plugin` project.

## Issues before PRs

1. When you are ready to start working on a change you should first [fork the repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [branch out](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-and-deleting-branches-within-your-repository) from the `dev` branch.
2. Make your changes.
3. [Open a pull request towards the `dev` branch in the main repo](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).

## Workflow

### Branches

All changes should be part of a branch and submitted as a pull request - your branches should be prefixed with one of:

- `feat/` for features
- `fix/` for bug fixes
- `hotfix/` for bug fixes
- `docs/` for documentation changes
- `chore/` for chores

### Commits

Strive towards keeping your commits small and isolated - this helps the reviewer understand what is going on and makes it easier to process your requests.

### Pull Requests

Once your changes are ready you must submit your branch as a pull request. Your pull request should be opened against the `dev` branch in the main repo.

In your PR's description you should follow the structure:

- **What** - what changes are in this PR
- **Why** - why are these changes relevant
- **How** - how have the changes been implemented
- **Testing** - how has the changes been tested or how can the reviewer test the feature

We highly encourage that you do a self-review prior to requesting a review. To do a self review click the review button in the top right corner, go through your code and annotate your changes. This makes it easier for the reviewer to process your PR.

#### Merge Style

1. Developer should create the pull request and request review from the team.
2. A team member (reviewer) will review the request and approve it.
3. The developer should merge the PR and via a merge commit. Origin branch should be deleted after merging.

### Documentation

- We generally encourage to document your changes through comments in your code.

### Release

The team will regularly create releases from the develop branch.
