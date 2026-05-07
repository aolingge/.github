# Aolingge Community Health Defaults

This special `.github` repository holds default community health files for repositories under `aolingge` that do not define their own templates.

## What Belongs Here

| File | Purpose |
| --- | --- |
| `.github/FUNDING.yml` | Shared sponsorship link. |
| `.github/pull_request_template.md` | Default pull request checklist for small repositories. |
| `.github/ISSUE_TEMPLATE/repo-improvement.yml` | Default issue form for documentation, verification, and repo-health improvements. |
| `.github/ISSUE_TEMPLATE/config.yml` | Issue-template settings. |

## Defaults Philosophy

- Keep templates short enough for small tools.
- Remind contributors to include verification evidence.
- Keep secrets, tokens, cookies, private paths, private URLs, browser profiles, and account data out of issues and pull requests.
- Let mature repositories override these defaults with project-specific templates.

## Maintainer Note

This repository is public because GitHub uses it as an account-level default. Do not store private operating notes, credentials, logs, browser data, or repository-specific secrets here.
