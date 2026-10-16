# OpenSAE Governance

OpenSAE is an open research and software organization. Each repository has its own scientific scope, maintainers, tests, and release history.

## Responsibilities

- **Project lead:** sets priorities, reviews larger technical changes, and resolves decisions that affect the shared research and engineering direction.
- **Maintainer:** reviews changes and tests, manages releases, and documents compatibility decisions for the repository they maintain.
- **Contributor:** proposes and implements changes through issues and pull requests, with reproducible evidence when relevant.

The current OpenSAE project lead and primary GitHub maintainer is [@AtheavenMa](https://github.com/AtheavenMa). These roles describe responsibilities, not a claim that additional staff or a governing committee currently exists.

## Decision process

Contributors can propose changes in the relevant repository. Maintainers review correctness, reproducibility, API compatibility, provenance, and maintenance cost before deciding whether to merge. Technical decisions should be documented in the issue or pull request.

SAEBase provides shared infrastructure. SAR, RSS, and Input Localization preserve the scientific definitions and original methods maintained in their individual repositories. Changes that affect those definitions require discussion with the relevant method maintainers.

Project-specific CODEOWNERS files identify responsible reviewers. Ownership may be delegated as additional maintainers join, with repository permissions updated accordingly. Releases and protected-branch settings remain governed by GitHub repository permissions.

We prefer a simple, documented decision process over committees that do not correspond to actual participants.
