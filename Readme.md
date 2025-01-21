# GitHub Actions Demo

This repository contains a simple demonstration of GitHub Actions.

## Workflow

The workflow file is located at `.github/workflows/github-actions-demo.yml`. It is triggered by a `push` event and runs a series of steps on an `ubuntu-latest` runner.

### Steps

1. **Trigger Notification**: Prints a message indicating that the job was triggered by a push event.
2. **Runner Information**: Prints the operating system of the runner.
3. **Branch and Repository Information**: Prints the branch name and repository name.
4. **Check out Repository Code**: Uses the `actions/checkout@v4` action to clone the repository to the runner.
5. **Clone Notification**: Prints a message indicating that the repository has been cloned.
6. **Ready to Test**: Prints a message indicating that the workflow is ready to test the code.
7. **List Files**: Lists the files in the repository.
8. **Job Status**: Prints the status of the job.

## Purpose

The purpose of this repository is to test and demonstrate the capabilities of GitHub Actions.
