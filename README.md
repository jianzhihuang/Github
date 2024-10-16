![Github](https://socialify.git.ci/jianzhihuang/Github/image?font=Jost&language=1&name=1&owner=1&pattern=Solid&stargazers=1&theme=Dark)
# Github
GitHub-activity
![Workflow name](https://github.com/jianzhihuang/Github/actions/workflows/stale.yml/badge.svg)

## Purpose and Usage

This repository is designed to measure developer activity on GitHub by generating random commit messages and pushing them to the repository. The purpose is to simulate developer activity and analyze the resulting data.

## GitHub Actions Workflow

The repository includes a GitHub Actions workflow defined in the `.github/workflows/stale.yml` file. The workflow is named "GitHub activity data as a measure of developer activity" and is triggered by a `workflow_dispatch` event or a scheduled cron job that runs every hour. It runs on the `ubuntu-latest` environment and includes several steps such as checking out the repository, generating random commit messages, and pushing commits to the repository. The workflow also includes a step to create a release using the `ncipollo/release-action@v1.13.0` action.

## Triggering the Workflow Manually

To trigger the workflow manually, follow these steps:

1. Go to the "Actions" tab of your repository on GitHub.
2. Select the "GitHub activity data as a measure of developer activity" workflow from the list.
3. Click on the "Run workflow" button.
4. Optionally, provide any necessary inputs for the workflow.
5. Click on the "Run workflow" button to start the workflow manually.
