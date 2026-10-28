# Experiment 3 — Branching and Merging

## Aim
Create a branch, make a change, and merge it into the main branch.

## Commands
```bash
git switch -c feature/update-notes
# Edit a file
git add .
git commit -m "Update notes on feature branch"
git switch main
git merge feature/update-notes
git log --oneline --graph --all
```

## Key concepts
- A branch lets you develop changes separately.
- A merge integrates changes from another branch.
- Review the merge result and run any relevant checks before pushing.

## Record your work
- Branch name:
- Change made:
- Merge result:
- Screenshot filename:
