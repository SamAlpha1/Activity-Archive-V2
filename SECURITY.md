# Security Policy

## Reporting a Vulnerability

Do not disclose vulnerabilities in public issues or pull requests.

Use GitHub's **Report a vulnerability** flow in this repository's Security tab when private vulnerability reporting is available. If unavailable, contact the repository owner privately through GitHub before public disclosure.

Include the affected version or commit, impact, reproduction steps, and relevant logs with all secrets removed.

## Supported Versions

Security fixes are applied to the latest maintained version on the default branch. Older releases are not guaranteed to receive updates.

## Secrets

Never commit API keys, tokens, private keys, passwords, seed phrases, or production credentials. Use environment variables and GitHub Actions secrets instead.
