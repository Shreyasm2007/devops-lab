# Experiment 2 — Remote Repositories

## Aim
Connect a local repository to GitHub and practice synchronizing changes.

## Commands
Replace the URL with your own repository URL.
```bash
git remote add origin https://github.com/YOUR-USERNAME/devops-lab.git
git remote -v
git branch -M main
git push -u origin main
git fetch origin
git pull origin main
git clone https://github.com/YOUR-USERNAME/devops-lab.git
```

## Notes
- `fetch` downloads remote updates without integrating them into the current branch.
- `pull` fetches and integrates changes.
- `push` sends local commits to the remote repository.
- `clone` creates a local copy of a remote repository.

## Record your work
- Commands executed:
- Result:
- Screenshot filename:
