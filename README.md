## Topic: Version Control using Git and GitHub:

- Commit,
- Branching,
- Merging, and Pull Requests

## Git Branching Practices Online

- **[Learngitbranching](https://learngitbranching.js.org/)**

## List of Useful Git Commands:

- **[Git Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)**
- **[Atlassian Commands](https://www.atlassian.com/git/glossary#commands)**
- **[Atlassain Cheatsheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)**

## 1. Configuration

- Check if Git is installed

```shell
git --version
```

- Set user name

```shell
git config --global user.name "Your Name"
```

- Set email

```shell
git config --global user.email "your-email@example.com"
```

- Check configuration

```shell
git config --list
```

## 2. Repository Initialization

- Initialize a new Git repository

```shell
git init
```

- Clone an existing repository

```shell
 git clone <repository_url>
```

## 3. Staging and Committing

- Check the status of changes

```shell
git status
```

- Add a single file to the staging area

```shell
git add <file_name>
```

- Add all files to the staging area

```shell
git add .
```

- Commit changes with a message

```shell
git commit -m "Your commit message"
```

## 4. Remote Repository Management

- Add a remote repository

```shell
git remote add origin <repository_url>
```

- View remote repositories

```shell
git remote -v
```

## 4. Git Pull & Push

- Pull latest changes from remote

```shell
git pull origin <branch_name>
```

- Push changes to a remote repository

```shell
git push origin <branch_name>
```

## 5. Branching

- Create a new branch

```shell
git branch <branch_name>
```

- Switch to a branch

```shell
git checkout <branch_name>
```

- Create and switch to a new branch

```shell
git checkout -b <branch_name>
```

- List all branches

```shell
git branch
```

## 6. Merging and Rebasing

- Merge a branch into the current branch

```shell
git merge <branch_name>
```

- Rebase the current branch onto another branch

```shell
git rebase <branch_name>
```

## 6. Undoing Changes

- Undo changes in a file

```shell
git checkout -- <file_name>
```

- Unstage a file

```shell
git reset HEAD <file_name>
```

- Amend the last commit

```shell
git commit --amend -m "New commit message"
```

- Revert a commit

```shell
git revert <commit_hash>

```

## 7. Statching Changes

- Save uncommitted changes

```shell
git stash
```

- List all stashes

```shell
git stash list
```

- Apply the latest stash

```shell
git stash apply
```

- Drop the latest stash

```shell
git stash drop
```
