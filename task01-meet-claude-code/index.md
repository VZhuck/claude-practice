# Task 1. Introduction to Claude Code
Target audience is engineers who has limited experience with claude code.

## Prerequisites

Before working with this repo, ensure the following software is installed:

### Node.js
- **Version**: 18 or higher
- **Install**: [https://nodejs.org](https://nodejs.org) (LTS recommended) or via a version manager:
  ```bash
  # macOS with Homebrew
  brew install node

  # Or use nvm (Node Version Manager)
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
  nvm install --lts
  ```
- **Verify**: `node --version` and `npm --version`

### Python
- **Version**: 3.11 or higher
- **Install**: [https://python.org](https://python.org) or via package manager:
  ```bash
  # macOS with Homebrew
  brew install python@3.12
  ```
- **Verify**: `python3 --version`

### uv (Python package manager)
`uv` is a fast Python package and project manager used to manage the backend dependencies and virtual environment.

- **Install**:
  ```bash
  # macOS / Linux
  curl -LsSf https://astral.sh/uv/install.sh | sh

  # Windows (PowerShell)
  powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

  # Or via Homebrew
  brew install uv
  ```
- **Verify**: `uv --version`
- **Docs**: [https://docs.astral.sh/uv](https://docs.astral.sh/uv)

### Git
- Required to clone the repository.
- **Install**: [https://git-scm.com](https://git-scm.com) (usually pre-installed on macOS/Linux)
- **Verify**: `git --version`



## Claude Workshop 

1. Go to https://claude-code-workshop.netlify.app/ 
2. Enter your name & workshop name `cbb-run-xxx`
3. Proceed with instructions there 
