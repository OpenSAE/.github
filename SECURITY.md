# Security Policy

OpenSAE maintains research software that may download third-party model and SAE checkpoints, datasets, or execute optional external integrations.

## Report a vulnerability privately

If the affected repository has GitHub private vulnerability reporting enabled, use its **Security → Report a vulnerability** option. Otherwise, email [hma232@wisc.edu](mailto:hma232@wisc.edu) with the subject “OpenSAE security report”.

Include the affected repository, version or commit, a description of the issue, and a minimal reproduction if it can be shared safely. Do not post exploit details, private data, or credentials in public issues.

The maintainers will evaluate the report and coordinate any necessary fix and disclosure. A specific response time is not currently guaranteed.

## Safe contributions

Review the provenance of third-party checkpoints and remote code. Use scoped, short-lived credentials, do not include tokens in logs or artifacts, and avoid adding binaries or datasets without distribution rights.

Repositories may provide more specific security instructions in their own SECURITY.md; those instructions take precedence.
