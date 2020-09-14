# github-playground
Playground to test GitHub &amp; Git

## CLI tool for GitHub

[cli/cli: GitHub’s official command line tool](https://github.com/cli/cli)

`gh` is a CLI tool developped by GitHub itself.

[github/hub: A command-line tool that makes git easier to use with GitHub.](https://github.com/github/hub)

There is also `hub` CLI tool for GitHub which is another popular one for a long time.

## How to use `gh` CLI

### Issue

You can create a issue from CLI by running the following command:

```shell
gh issue create --repo "$REPOSITORY" --title "$ISSUE_TITLE" --body "$ISSUE_BODY"
```

### Pull-Request

You also create a pull-request to the upstream repository from the current local branch:

```shell
gh pr create --base master --title "$PULL_REQUEST_TITLE" --body 'This PR closes #123456.'
```
