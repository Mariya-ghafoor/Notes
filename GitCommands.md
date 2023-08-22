# Git Commands

## Branches

```bash
#create a new branch and switch to it
git checkout -b branch_name
git switch --create branch_name
```

## Unstaged Changes

```bash
#restore back to the original state in a file with an unstaged change
git restore file_name

#retore back to the original state of a branch by removing unstaged files
git clean -n #this will tell you which files will be deleted

git clean -f #this will forcefully delete the files
```

## Staged Changes

```bash
#Unstage the changes that were staged
git restore --staged file_name

```

## Committed Changes
