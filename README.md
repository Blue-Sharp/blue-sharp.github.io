# blue-sharp.de

Personal CV/resume website for Rafael Kansy, hosted on GitHub Pages.

## Setup

After cloning, activate the pre-commit allow-list hook:

```sh
chmod +x scripts/pre-commit
git config core.hooksPath scripts
```

This hook prevents files not on an explicit allow-list from being committed — important because this is a public repository. See `scripts/pre-commit` for the full allow-list.
