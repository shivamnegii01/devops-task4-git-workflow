# DevOps Task 4 – Git Version Control Workflow

## Objective

Manage a DevOps project using Git and GitHub best practices.

## Tools Used

- Git
- GitHub
- VS Code

## Git Workflow

This project demonstrates a basic Git branching and pull request workflow.

```text
main
  │
  └── dev
       │
       └── feature/git-documentation
```

The feature branch is used for development work. Changes are committed and pushed to GitHub, then a Pull Request is created to merge the feature branch into `dev`.

After the development work is completed, another Pull Request is created to merge `dev` into `main`.

## Branches

- `main` – Stable/main project branch
- `dev` – Development branch
- `feature/git-documentation` – Feature branch for documentation work

## Git Concepts Demonstrated

- Repository initialization
- Branching
- Commits
- Pull Requests
- Merging
- `.gitignore`
- Git tags
- Markdown documentation
- Git workflow

## Project Documentation

Detailed Git workflow documentation is available in:

`docs/git-workflow.md`

## Git Tag

The completed project will be marked with:

`v1.0.0`

## Outcome

This project demonstrates how Git and GitHub can be used to manage a DevOps project using branches, commits, pull requests, tags, and documentation.