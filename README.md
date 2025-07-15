# Sagar-classes

GIT stash Use Case:
You're working on a feature, made some changes, and now need to switch branches (e.g., to fix a bug) without committing your current work. You don’t want to lose your changes either.

Example Scenario:
You’re on feature-x and made some changes to file1.py and file2.js. Now, your manager asks you to immediately fix something in the main branch.

Step 1: Save Current Work Without Committing
git stash
This stashes (temporarily saves) all tracked file changes and resets your working directory to match the last commit.

Step 2: Switch to Another Branch
git checkout main
Now you're free to fix the urgent bug.

 Step 3: Return and Reapply Your Changes
 git checkout feature-x
git stash pop
This re-applies your previously stashed changes to feature-x and removes the stash.
