# GitHub Daily Contribute

This repository contains an automated GitHub Action that makes a daily commit to keep the GitHub contribution graph green.

## How it works

The workflow runs every day at 00:00 UTC using GitHub Actions. It appends the current date and time to `contribution.log` and pushes the commit back to the repository.

This uses the account name `Sandept` and email `san.dept008@gmail.com` to ensure the commits are correctly attributed to the user's contribution graph.
