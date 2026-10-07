# Git Workflow Documentation

## 1. Repository Initialization

The project was initialized as a Git repository and connected to GitHub.

```bash
git init
git remote add origin <repository-url>
```

## 2. Main Branch

The `main` branch represents the stable version of the project.

## 3. Development Branch

A `dev` branch is used for development work.

```bash
git checkout -b dev
```

Changes can be developed and tested on this branch before they are merged into `main`.

## 4. Feature Branch

A separate feature branch is created for specific work.

```bash
git checkout -b feature/git-documentation
```

The feature branch keeps the work isolated from the development and main branches.

## 5. Commits

Changes are recorded using Git commits.

Example:

```bash
git add .
git commit -m "Add Git workflow documentation"
```

Each commit provides a record of the changes made to the project.

## 6. Pull Requests

After completing work on the feature branch, the branch is pushed to GitHub and a Pull Request is created.

Workflow:

```text
feature/git-documentation
          ↓
       Pull Request
          ↓
          dev
```

After the development work is completed:

```text
dev
 ↓
Pull Request
 ↓
main
```

## 7. Git Tag

After the project is completed, a version tag is created.

```bash
git tag v1.0.0
git push origin v1.0.0
```

The tag identifies the completed version of the project.

## 8. Git Stash

`git stash` temporarily saves uncommitted changes.

Example:

```bash
git stash
```

The changes can later be restored using:

```bash
git stash pop
```

## 9. Merge and Rebase

### Merge

Merge combines changes from one branch into another while preserving the branch history.

### Rebase

Rebase moves commits onto another base commit and creates a more linear history.

For this project, Pull Requests and merging are used to demonstrate the required Git workflow.

## 10. Merge Conflict

A merge conflict can occur when Git cannot automatically combine changes from different branches.

The conflict can be resolved by editing the affected file, removing the conflict markers, and then committing the resolved changes.

## 11. Outcome

This project demonstrates Git version control using:

- Branches
- Commits
- Pull Requests
- Merging
- `.gitignore`
- Git tags
- Markdown documentation

## 12. Feature Branch Workflow

This project uses a feature branch to develop changes separately from the `dev` and `main` branches.

The workflow is:

```text
feature/git-documentation
          ↓
       Pull Request
          ↓
          dev
          ↓
       Pull Request
          ↓
         main
```

Using a feature branch keeps development work isolated and allows the changes to be reviewed through a Pull Request before merging.