# Repo for practice git commands

git add FILE or . -> stage selected files on staging area

git commit -m "Message" -> save the changes on staging area

git commit --amend -> incorporate new changes to a commit

# Stash changes

git stash -> save the changes temporarily, it works locally

git stash pop -> reapply the changes and delete from stash area

git stash apply -> reapply the changes but not delete from stash area

git stash list -> show stashed changes

git stash save "message" -> stash changes with an description

git stash pop IDENTIFIER -> reapply the specific stash (use list for obtain identifiers)

git stash clear -> delete all stashes

git stash branch branch_name stash_id -> create a new branch where reapply the changes of specific stash
