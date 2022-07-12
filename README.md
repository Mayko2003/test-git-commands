# Repo for practice git commands

# FETCH

git fetch -> update local repo from remote repo, it only works for check if there are changes

# PULL

git pull -> it does a git fetch for check if there are changes and then a git merge for include change

# MERGE

git merge branch_name -> merges changes from another branch to actual branch, it create a merge commit

Requirements for merges: you must not have pending changes, 

# REBASE

git rebase branch_name -> perform a merge but with a base change, DONT USE IN PUBLIC BRANCH

git rebase -i HEAD~N -> use interactive rebase

# CHERRY-PICK

git cherry-pick commit_id -> adds a commit to current branch, it usually can be used to incorporate a commit from another branch