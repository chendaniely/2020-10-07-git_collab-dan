# 2020-10-07-git_collab-dan
Git collaboration

- `git clone <URL>`: downloads the repo from the URL to your computer
    - make sure you are not already in a git repo when you `clone`

## Branches

- `git branch <NAME>`: creates a branch <NAME> where you currently are (HEAD)
- `git branch -a`: shows you all local and remote branches
- `git checkout <BRANCH>`: switch to the <BRANCH>
- `git checkout -b <BRANCH>`: create <BRANCH> and then also checkout out <BRANCH>

## Pull requests (online merge aka merge request)

- `git log --oneline --graph --all`: shows you your git history tree
- `git fetch --prune`: delete local references to delted remote branches
- `git fetch`: updates local references with remotes
- `git branch -d <BRANCH>`: delete local <BRANCH>

## Conflicts

- update your branches (e.g., `git checkout main`; `git pull origin main`)
- go to conflicting branch: `git checkout <BRANCH>`
- `git rebase main`: will rebase <BRANCH> again `main`
