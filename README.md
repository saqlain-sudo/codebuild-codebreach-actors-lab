# CodeBuild CodeBreach Actors Lab

Inntentionally vulnerable training repository for AWS CodeBuild webhook filter misconfigurations.

## Safety note
This repository is for training only.

⚠️ If multiple users attempt to establish a reverse shell simultaneously, connections may collide or be hijacked, resulting in unexpected session behavior.

## PR Cleanup Policy

This repository is reset automatically by an hourly GitHub Action:

- **Non-seed PRs** (regular student PRs) are closed every hour.
- **Seed PRs** labeled `lab-seed-pr` are kept open for discoverability and only closed after they are at least **12 hours** old.

The seed PR is used so students can quickly find a successful CodeBuild check URL directly from the repository UI.
