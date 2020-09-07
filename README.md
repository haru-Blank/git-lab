# Useful Git Commands

Quickly need to find a Git command? Here is your little helper:

- `git init`: Initialize a Git repository in the current folder
- `git status`: Show the current status of your Git repository (the “working tree” status)
- `git add .`: Track changes of all files in your Repository
- `git commit -m "your message"`: Save updated code to a new Commit named “your message”
- `git log`: List all Commits inside your Branch
- `git checkout branch-name`: Jump to the last Commit of a Branch
- `git checkout commitid` Jump to a specific Commit of a Branch (commitid should be the ID of the Commit you want to checkout)
- `git checkout -- .`: Jump back to the last Commit and remove any untracked changes
- `get reset --hard`: Turn the selected Commit into the new HEAD
- `git branch`: List all Branches inside your Repository
- `git checkout -b branch-name`: Create a new Branch named branch-name
- `git merge branch-name`: Merge two Branches, branch-name is the Branch you merge with the Branch you’re currently working in
- `git branch -D branch-name`: Delete the Branch named branch-name

