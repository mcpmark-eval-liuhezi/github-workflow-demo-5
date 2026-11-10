# Workflow Audit

End-to-end walkthrough of how branches, pull requests, issues, and close-out fit together on this repository.

## Branch

A feature branch (`feature/audit-notes`) is created from the default branch (`main`) before any work begins. Changes stay isolated on the branch until they are ready to be reviewed, which keeps the default branch stable for everyone else.

## Pull Request

Once the write-up is committed on the feature branch, a pull request is opened from `feature/audit-notes` into `main`. The PR is the place where the change gets reviewed, discussed, and either approved or reworked before it can land.

## Issue

An issue tracks work at a higher level than a PR: what needs doing, why it matters, and what success looks like. One issue — "Demo: workflow checklist" — captures the open work, and smaller follow-up issues can be attached as sub-issues so there is one linked record per piece of work.

## Close-Out

When the checklist is done, a comment is posted on the checklist issue and the issue is closed as completed, while any remaining follow-up issues stay open. Close-out makes it obvious what is finished and what is still pending.

## Owner

- **Login:** HeziLiu
- **Display name:** Hezi Liu
- **Bio:** treat me like a tree
- **Location:** Beijing/Guiyang
- **Company:** BUPT/GZU
- **Profile:** https://github.com/HeziLiu
