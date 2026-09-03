# Git & GitHub Cheatsheet

A short, practical reference for the Git and GitHub commands you'll use most often.

## Basic Git Workflow

| Command | What it does |
| --- | --- |
| `git status` | Show changed, staged, and untracked files |
| `git add <file>` | Stage a file for the next commit |
| `git commit -m "message"` | Commit staged changes |
| `git push` | Upload commits to the remote repository |
| `git pull` | Download and merge remote changes |

## Branching

| Command | What it does |
| --- | --- |
| `git branch` | List local branches |
| `git checkout -b <name>` | Create and switch to a new branch |
| `git switch <name>` | Switch to an existing branch |
| `git merge <name>` | Merge a branch into the current one |

## Inspecting History

| Command | What it does |
| --- | --- |
| `git log` | Show commit history |
| `git diff` | Show unstaged changes |
| `git diff --staged` | Show staged changes not yet committed |

## GitHub CLI (`gh`)

| Command | What it does |
| --- | --- |
| `gh auth login` | Authenticate the CLI with your GitHub account |
| `gh repo create` | Create a new repository on GitHub |
| `gh repo clone <owner>/<repo>` | Clone a repository locally |
| `gh pr create` | Open a pull request from the current branch |

## Tips

- Write commit messages in the imperative mood: "Fix bug" not "Fixed bug".
- Keep pull requests small and focused on a single change.
- Pull before you push to avoid unnecessary merge conflicts.
