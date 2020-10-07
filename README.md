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

## Collaboration

- add person as a collaborator

# Some additional notes and links

- Software Carpentry notes on basic git: https://swcarpentry.github.io/git-novice/
    - The setting up git has the commands to setup your name/email/editor: https://swcarpentry.github.io/git-novice/02-setup/index.html

- Git workflow notes and commands (to paste on your wall)
    - https://chendaniely.github.io/training_ds_r/help-faq.html

- Atlassian page on git workflows: https://www.atlassian.com/git/tutorials/comparing-workflows
    - The one we covered today was mainly the "Feature Branch Workflow": https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow

- The atlassian page has more infor about "git flow", but this is also another top Google hit that I liked:
  - https://nvie.com/posts/a-successful-git-branching-model/

- Getting your (bash) terminal to show current path and other things:
    - Use this to create your PS1 variable: http://bashrcgenerator.com/

- Show git branch in terminal:
    - In addition you can write a function and put that in your PS1 to also show git branch
    - https://gist.github.com/joseluisq/1e96c54fa4e1e5647940
    
- Video I did with more forking related workflow: https://www.youtube.com/watch?v=uvWhSYBkZJ0

- Setting up ssh links: https://bi-sdal.github.io/training/ssh-keys.html
- https://happygitwithr.com/ (more rstudio specific workflows)
