# CLAUDE.md

## Project Overview

This is a **GitHub profile repository** for the user `AMG-Nav`. Repositories named after a GitHub username are special — the `README.md` automatically appears on the user's GitHub profile page.

The owner is interested in **Data Engineering** and is currently learning **Python3 & Spark**.

## Repository Structure

```
AMG-Nav/
├── README.md                      # GitHub profile page content
├── CLAUDE.md                      # This file — guidance for AI assistants
└── .github/
    └── workflows/
        └── blank.yml              # GitHub Actions CI workflow (template)
```

## Key Files

- **`README.md`** — The profile README displayed on the GitHub profile page. Contains a brief personal introduction.
- **`.github/workflows/blank.yml`** — A template GitHub Actions workflow triggered on push/PR to `main`. Currently runs placeholder echo commands with no real build, test, or deploy steps.

## Development Workflow

### Branches

- **`main`** — The default/production branch. CI triggers on push and PR to this branch.

### CI/CD

- GitHub Actions is configured (`.github/workflows/blank.yml`) but only contains template placeholder steps.
- No real build, test, or deployment pipeline is implemented yet.

### Build & Test

- **No build system** — No `package.json`, `setup.py`, `requirements.txt`, `pyproject.toml`, or `Makefile` exists.
- **No test framework** — No tests are configured or available to run.
- **No linting/formatting** — No linter or formatter is configured.

## Conventions

- This is a profile repository, not an application. Changes should primarily be to `README.md` content or CI configuration.
- The README uses GitHub-flavored Markdown with emoji shortcodes.
- Keep profile content concise and personal.

## Notes for AI Assistants

- There is no source code to build or test. Do not attempt to run build/test commands.
- When modifying `README.md`, preserve the existing personal style and emoji usage.
- The HTML comment block in `README.md` (`<!--- ... --->`) is a GitHub-generated hint and can be left as-is or removed per user preference.
- Any new workflows added to `.github/workflows/` should follow the existing pattern of targeting the `main` branch.
