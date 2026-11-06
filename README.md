# Git Branch Workflow

## Project Description

This project demonstrates Git branch management and commit conventions. It was created as part of a practical laboratory assignment.

The project focuses on using three main types of branches: `main`, `develop`, and `feature/*`.

## Development Setup

### Requirements
- Git
- Visual Studio Code
- GitHub account

### Repository initialization

```bash
git init -b develop
```

### Author configuration

```bash
git config user.name "Aiken Kazbalinova"
git config user.email "your-email@example.com"
```

### Merge configuration

```bash
git config branch.main.mergeoptions "--no-ff"
git config branch.develop.mergeoptions "--no-ff"
```

## Branching Strategy

- `main` — stable and tested releases.
- `develop` — integration branch.
- `feature/*` — development of new features.

## Commit Convention

Commit messages follow the Conventional Commits guideline.

## Additional Guidelines

See the additional branching and commit guidelines provided with the laboratory assignment.
