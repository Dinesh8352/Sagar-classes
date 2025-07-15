# Sagar-classes

GIT stash drop Use Case:

You used git stash to temporarily save some changes, but later realize you no longer need those stashed changes and want to delete a specific stash entry.
You’ve stashed multiple times
git stash list
You decide that the stash@{1} is outdated and no longer useful.
Step: Delete That Specific Stash
git stash drop stash@{1}
This will delete only the stash entry at index 1 and leave others intact.