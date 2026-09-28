<!-- Headings -->
# ![Git](https://img.icons8.com/?size=40&id=118553&format=png&color=000000)***Git Practice Workshop Repository***

## ![pin logo](https://img.icons8.com/?size=32&id=4WKEF9tBOcwU&format=png&color=000000)*About this Repository*

#### This repository is created for practicing **Git Commands**.

## ![Task](https://img.icons8.com/?size=30&id=1TCX2ww987mj&format=png&color=000000)*Task 1:*

1. Create Local repository.
2. Connect to Github
3. Track changes
4. Ignoring files

## ![Task](https://img.icons8.com/?size=30&id=1TCX2ww987mj&format=png&color=000000)*Task 3:*

## 🌿 Branching and Merging

* Created and worked on the [`padma-update` branch](https://github.com/Padmaqaauto/Git_Workshop/tree/padma-update).
* Practiced switching between branches and merging changes.

## 🤝 Collaborating with Pull Requests

* Forked [`Ezhilarasi28/Git_Workshop`](https://github.com/Ezhilarasi28/Git_Workshop) to my GitHub account: [`Padmaqaauto/Git_Workshop`](https://github.com/Padmaqaauto/Git_Workshop).
* Created changes in my fork and practiced creating a Pull Request back to the original repository.
* Practiced reviewing and collaborating through Pull Requests.

## ⏮️ Revert and Reset

* Practiced `git revert`, `git reset`, and `git restore` to undo or manage changes.

## 🏷️ Tagging and Releases

* Created and worked with the `v1.0.0` tag.
* Practiced switching between project versions using tags.
* Practiced viewing and pushing tags and preparing release notes for `v2.0.0`.



## ![Command](https://img.icons8.com/?size=30&id=GOJfNTFsVeOY&format=png&color=000000)*Git Commands and their definitions*

| Command                        |  Definition  |
| -----------------------------  | ------------ |
| `git config --list`            |  To see all your git settings|   
| `git config --list --global`   |  Displays the Git configuration settings defined at the global user level.| 
| `git config --list --system`   |  Displays Git configuration settings defined at the system level.| 
| `git --version`                |  Displays the installed Git version. |
| `mkdir git-workshop-practice`  |  Creates a new directory named git-workshop-practice. |
| `cd git-workshop-practice`     |  Changes the current working directory to git-workshop-practice.|
| `git init`                     |  Initializes a new, empty Git repository in your current folder. |
| `git status`                   |  Shows the current state of your project.  |
| `git add <file>`            | Adds a specific file to the staging area. |
| `git commit -m "Your message"` |  Saves a snapshot of your staged changes with a descriptive message. |
| `git log`                      | Shows a chronological list of all commits made in the repository.|
| `git log --oneline`            |  A simplified, compact version of the history.|
| `git diff`                     |  Shows exactly what lines were added or removed in your files since the last save.|
| `git remote add origin`        |  Add the remote address |
| `git remote -v`                |  Verify the remote connection |
| `git branch`                   |  To see all branches in your repository | 
| `git branch -M main`           |  Rename your current Git branch to main |
| `git push -u origin main`      |  Upload your local 'main' branch to the remote 'origin' |
| `git branch <branchname>`      |  Creates a new branch with the "branchname" |
| `git checkout <branchname>`    |  Moving us from the current branch, to the one specified at the end of the command. |
| `git push --set-upstream origin`| Use this if your branch doesn't exist on GitHub yet, and you want to track it |
| `git commit -a -m "message"`   |  Stage all modified and deleted files that are already tracked by Git, and commit them with the specified message.| 
| `git push`                     |  Pushes the current local branch to its configured remote/upstream branch. |
| `git push origin <branch_name>`|  Pushes the local update-readme branch to the update-readme branch on the remote repository named origin.|
| `git add --all`                |  Stages all new, modified, and deleted files in the entire repository.| 
| `git stash`                    |  Saves your uncommitted changes and return to a clean working directory. |
| `git stash pop`                |  Apply the latest stash and remove it from the stack. |
| `git pull origin`              |  Pull all changes from a remote repository into the branch you are working on. |
| `git revert HEAD`              |  Revert the latest commit |
| `git restore readme.md`        |  Restore deleted or changed a file|
| `git restore --staged <file>`  |  Unstage a file            |
| `git reset --soft HEAD~1`      |  undo the last commit and keep your changes staged. |
| `git log --stat`               |  To see which files changed in each commit |
| `git stash push -m "message"`  |  Stash with a message |
| `git stash list`               |  List all stashes          |
| `git stash show`               |  Show stash details        | 
| `git stash show -p`            |  Shows the exact lines that were changed in your most recent stash.|
| `git stash apply`              |  Restores your most recent stashed changes, but keeps the stash in the list so you can use it again if needed.|
| `git show <commit>`           |  Show details of a specific commit|
| `git switch -c <branch-name>` |  Creates a new branch and switches to it immediately.     |
| `git remote set-url <remote-name> <repository-url>` | Changes the URL of an existing remote repository. Here, origin is changed to your GitHub repository. |
| `git tag`                     |  Lists all tags available in the local repository.  |
| `git log --oneline -<number>`  |  Displays the specified number of recent commits in a short, one-line format. |
| `git tag <tag-name>`           |  Creates a tag named "tagname" pointing to the current commit.  |
|`git show <tag-name>`           |  Displays information about the commit and changes associated with the specified tag. |
| `git push <remote-name> <tag-name>` |  Pushes the specified tag from your local repository to the remote GitHub repository. |
| `git switch --detach <tag-name>`    | Switches to the specified tag/version and puts Git into detached HEAD mode. |
| `git commit --amend --no-edit`    | Add the changes to your previous commit and keeps the previous commit message unchanged |
| `git push --force-with-lease origin main` | Push my updated main branch to GitHub and replace the previous version, but only if nobody else has changed it.|












