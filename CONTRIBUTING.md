# Contributing to OpenSAE

Thank you for helping make research on sparse autoencoders and neural representations easier to reproduce and build upon.

## Find the right project

- [SAEBase](https://github.com/OpenSAE/SAEBase) maintains shared model and SAE integration, activation caching, feature interventions, and evaluation infrastructure.
- [SAR](https://github.com/OpenSAE/SAE-Behavioral-Compositionality), [RSS](https://github.com/OpenSAE/Redistribution-Sensitivity-Score), and [SAE Input Localization](https://github.com/OpenSAE/SAE-Input-Localization) maintain their respective research methods, demonstrations, and tests.

Each repository's README and project-specific contributing instructions take precedence over this organization-wide guide.

## How to contribute

1. Search existing issues and pull requests before proposing a change. Open a focused issue for new functionality or support requests.
2. Fork or branch from the current default branch. Keep one change per pull request.
3. Describe what changed, why it matters, and how it was tested. Include the smallest reproducible example for bug fixes.
4. Run the tests and examples documented by the target repository. State clearly which real-checkpoint or GPU checks were not run.
5. Link original code, papers, checkpoints, revisions, and licenses whenever your contribution uses an external asset.

Documentation improvements, tests, model compatibility fixes, and review of existing examples are welcome. Significant API or scientific-protocol changes should be discussed before implementation.

## Research and reproducibility

Keep a clear distinction between synthetic tests, checkpoint loading, real model-SAE pair validation, engineering benchmarks, and scientific conclusions. Include exact model and SAE identifiers, layers and hooks, versions, selection/evaluation splits, and random seeds where relevant.

Do not silently replace a paper's original estimator, redefine a metric, or claim that a registered checkpoint was verified without real evidence. Do not commit private data, access tokens, model weights without redistribution rights, or oversized experiment caches.

## Collaboration

Be constructive and respectful. Read the [Code of Conduct](CODE_OF_CONDUCT.md), [Support](SUPPORT.md), and [Security Policy](SECURITY.md). For how decisions are made, see [Governance](GOVERNANCE.md).
