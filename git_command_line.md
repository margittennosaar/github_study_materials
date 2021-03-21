# Git commands you should know

## Git setup

| Command                                                | Description                                                            |
| ------------------------------------------------------ | ---------------------------------------------------------------------- |
| `git config --global user.name “[firstname lastname]”` | set a name that is identifiable for credit when review version history |
| `git config --global user.email “[valid-email]”`       | set an email address that will be associated with each history marker  |
| `git status`                                           | changed files in your working directory                                |
| `git remote -v`                                        | list all currently configured remotes                                  |

## Git basics

| Command                | Description                                        |
| ---------------------- | -------------------------------------------------- |
| `git init`             | create empty Git repo in specified directory       |
| `git clone <repo url>` | clone repo located at `<repo>` onto local machine. |
| `git status`           | changed files in your working directory            |
| `git remote -v`        | list all currently configured remotes              |

## Local changes

| Command                     | Description                                                      |
| --------------------------- | ---------------------------------------------------------------- |
| `git add .`                 | stage all changes for the next commit                            |
| `git add <directory>`       | stage all changes in `<directory>` for the next commit           |
| `git reset <file>`          | unstage a file while retaining the changes in working directory  |
| `git diff`                  | diff of what is changed but not staged                           |
| `git diff --staged`         | diff of what is staged but not yet commited                      |
| `git commit -m "<message>"` | Commit the staged snapshot and include message about this commit |

## Commit history

| Command            | Description                            |
| ------------------ | -------------------------------------- |
| `git log`          | show all commits, starting with newest |
| `git blame <file>` | show who shanged what and when         |

## Branches

| Command                    | Description                                                           |
| -------------------------- | --------------------------------------------------------------------- |
| `git branch`               | list all existing branches                                            |
| `git checkout <branch>`    | switch to another branch and check it out into your working directory |
| `git checkout -b <branch>` | make new branch and switch HEAD branch                                |

## Remote repositories

| Command                       | Description                                                                                                                           |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| `git remote add <url>`        | create a new connection to a remote repo.                                                                                             |
| `git fetch <remote> <branch>` | fetches a specific `<branch>`, from the repo. Leave off `<branch>` to fetch all remote refs.                                          |
| `git pull <remote>`           | fetch the specified remote’s copy of current branch and immediately merge it into the local copy.                                     |
| `git push <remote> <branch>`  | Push the branch to `<remote>`, along with necessary commits and objects. Creates named branch in the remote repo if it doesn’t exist. |

## Merge and rebase

| Command               | Description                                               |
| --------------------- | --------------------------------------------------------- |
| `git merge <branch`   | merge the specified branch’s history into the current one |
| `git log`             | show all commits in the current branch’s history          |
| `git rebase <branch>` | rebase your current HEAD onto `<branch>`                  |

## Undo

| Command               | Description                                                |
| --------------------- | ---------------------------------------------------------- |
| `git reset`           | merge `<branch>` into your current HEAD                    |
| `git rebase <branch>` | apply any commits of current branch ahead of specified one |
