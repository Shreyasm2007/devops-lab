# Experiment 4 — Merge Conflicts and Rebasing

## Aim
Understand how to resolve a conflict and review the resulting history.

## Conflict-resolution outline
1. Make conflicting edits to the same lines on two branches.
2. Attempt a merge.
3. Open the conflicted file and locate the conflict markers.
4. Edit the file to keep the intended final content.
5. Stage the resolved file and complete the merge.

## Commands
```bash
git status
# Edit the conflicted file and remove conflict markers
git add <resolved-file>
git commit
```

## Rebasing practice
Use a disposable practice branch first:
```bash
git switch feature/update-notes
git fetch origin
git rebase origin/main
```

If conflicts occur during rebase, resolve them and use `git add <file>` followed by `git rebase --continue`. Use `git rebase --abort` to return to the pre-rebase state. Avoid rebasing shared branches without agreement.

## Record your work
- Conflict encountered:
- Resolution:
- History observed:
