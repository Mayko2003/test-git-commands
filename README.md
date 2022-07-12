# Repo for practice git commands

USE IN COMBINATION WITH LOG COMMAND

# Undo changes with checkout

git checkout HASH_COMMIT -> change HEAD to specific commit and you can make experimental changes

aditional: you can use git checkout -b branch_name for create a branch with undo changes

# Undo changes with revert

git revert HEAD -> revert changes but not revert history of commits, it adds a new commit for
revert the changes

# Undo changes with reset

git reset --hard/soft HEAD~1 -> delete last commit, --hard=delete changes and commit, --soft=only delete the commit

git reset --hard/--soft HASH_COMMIT -> back to a specified commit

# Restoring files

git restore --options PATH_SPEC -> restore a file 

example: git restore '*.c' -> restore all C source files of current index

example2: git resore --source HEAD~2 MakeFile -> restore MakeFile from another commit

# Additional

git clean -> delete untracked files, it needs to be executed with --force option due to security reasons