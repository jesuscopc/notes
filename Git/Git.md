# Git commands

|Indice|
|---------|
|[How to undo a git commit](#how-to-undo-a-git-commit)|
|[How to revert a commit](#how-to-revert-a-commit)|

## **How to undo a git commit**

### 1. Amend no-edit
Let's start with the easiest situation, you already did a commit but you forgot to add some files.
Instead of creating an extra commit on top, you can run git commit --amend --no-edit. As a result, the last commit will be updated with the new files.

```bash
git add .
git commit --amend --no-edit
```

### 2. Amend & Change Message
Similar situation to the previous one, but you also want to change the commit message.

```bash
git add .
git commit --amend
```

## **How to revert a commit**
Did you ever create a commit that you wish never happened?

```bash
git revert [here comes the commit id]
```
Let's say, your commit id is 17hg8w. You would call it like this:

```bash
git revert 17hg8w
```

Note that this operation creates a new commit that reverts all of the changes instead of removing given commit from history.