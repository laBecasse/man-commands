# Git 

## add 

We can use the flag ` add -p` in order to add only a part of a file. 

## commit

The flag `--amend` allows to modify the last commit, only use **before push**.

## reset 

Delete the last commit, if there is no modified file since.

The flag `--hard` is **dangerous** and delete modified files

## checkout 

- `git checkout file` reset the staged file to the last commit and **delete the unstaged changes**.
- `git checkout file commit` reset the staged file to `commit` and **delete the unstaged changes**.

## branch 

Create a branch on the current commit.

## diff 

We use this command to see the changes between the actual directory and the last commit.

## log 

Display the history of the commits

## rm 

The two following commands are equivalentes:
```sh
git rm file
rm file && git add file
```

## remote 

We can add remote repository with: 

`git remote add <local-name> <url>`

## rebase

Rebase put a branch after other branch. Be careful with it, if you rebase on a remote branch.

