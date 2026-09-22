# Git Playground

A hands-on repository for learning Git and GitHub features through small, repeatable experiments.

## What I Am Practicing

- Creating repositories and making commits
- Checking status, history, and differences
- Working with branches and merging changes
- Resolving merge conflicts
- Using remotes, `fetch`, `pull`, and `push`
- Opening pull requests and reviewing code
- Tagging releases
- Using `.gitignore`
- Rewriting local history with `reset`, `restore`, and `rebase`
- Automating checks with GitHub Actions

## Useful Git Commands

```bash
# Start a repository and inspect its state
git init
git status

# Record changes
git add .
git commit -m "Describe the change"

# Explore history and changes
git log --oneline --graph --decorate
git diff

# Work with branches
git switch -c feature/example
git switch main
git merge feature/example

# Connect to GitHub and synchronize
git remote -v
git fetch origin
git pull origin main
git push -u origin main
```

## Suggested Practice Flow

1. Make a small change and commit it.
2. Create a feature branch and make another change.
3. Merge the branch into `main`.
4. Create a conflict in two branches and resolve it.
5. Push the repository to GitHub.
6. Open a pull request, review it, and merge it.
7. Add a GitHub Actions workflow and create a release tag.

## Notes

This repository is intentionally experimental. Each commit can document a Git or GitHub feature, command, or lesson learned.
