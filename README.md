# commit-bot

Keeps your GitHub contribution graph active via a daily GitHub Actions workflow. No local setup needed — runs entirely in the cloud.

## How it works

A scheduled workflow runs at 10 PM UTC every day, appends a timestamp to `activity.log`, and pushes a commit. That commit counts as a contribution.

## Setup

1. Fork or clone this repo to your GitHub account
2. Go to **Settings → Actions → General** and ensure "Read and write permissions" is enabled under Workflow permissions
3. That's it — the workflow runs automatically every night

You can also trigger it manually any time from the **Actions** tab using "Run workflow".
