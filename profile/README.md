![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103) [![GitHub license](https://img.shields.io/badge/licence-GPL--3.0-blue)](LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-green.svg)](.github/CONTRIBUTING.md)
<br>

# unix-terminal-setup

A couple of repositories with bash scripts to setup terminal utilities, for quickly setting up a new Linux or MacOS machine.

## Shell Scripting Notes

- Scripts are written in `Bash`.
- Shebang is by default: `#!/usr/bin/env bash`
- All scripts include `set -euo pipefail` to add safety options, which will stop execution if a command fails, pipe command fails or trying to use
  undefined variables.
- Initial focus is on using these on the `Ubuntu distro` (apt/snap) and `MacOS Sonoma` (brew).
