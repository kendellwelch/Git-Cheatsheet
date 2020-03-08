Hello Git and Github

Connecting and pushing to github:
git remote add origin https://github.com/Cynddelw/git_practice2.git
git push -u origin master

Git Commands:

    git init creates a new Git repository
    git status inspects the contents of the working directory and staging area
    git add adds files from the working directory to the staging area
    git add filename_1 filename_2 adds multiple
    git diff shows the difference between the working directory and the staging area
    git commit permanently stores file changes from the staging area in the repository
    git log shows a list of all previous commits

Git Backtrack:

    git checkout HEAD filename: Discards changes in the working directory.
    git reset HEAD filename: Unstages file changes in the staging area.
    git reset commit_SHA: Resets to a previous commit in your commit history.

Git Branching:

    git branch: Lists all a Git project’s branches.
    git branch branch_name: Creates a new branch.
    git checkout branch_name: Used to switch from one branch to another.
    git merge branch_name: Used to join file changes from one branch to another.
    git branch -d branch_name: Deletes the branch specified.
