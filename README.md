# Git & Github

## What is Version Control?

Version control is like a time machine for your files. It tracks changes, lets you rewind to earlier versions, and helps multiple people work together without chaos. This means safer backups, smoother collaboration, and easier bug tracking, making it a must-have for any project!

## What is the difference between Git and Github?

Git is your local code time machine, letting you track changes and rewind. GitHub is the online bookshelf where you store those versions, collaborate with others, and share your coding adventures!

## Some other Github Alternatives

- GitLab.
- Bitbucket.
- Codeberg.

## Difference between `git fetch` and `git pull`

- **git fetch:** Downloads the latest changes from the remote repository to your local repository without merging them into your current branch. This means you have access to the updates, but your working directory and current branch remain unchanged.
- **git pull:** Is essentially a shorthand for `git fetch` followed by `git merge.` It downloads the latest changes from the remote repository and attempts to merge them into your current branch. If the merge is successful, your working directory is updated with the combined changes. However, if there are conflicts between local and remote changes, you'll need to resolve them manually before continuing.

## `git cherry-pick`

Imagine a cherry tree full of commits (changes). Cherry-pick lets you pluck a specific, delicious commit from one branch and place it on another branch, without bringing along the entire branch history.

Here's how it works:

- **Find the commit you want:** Use `git log` to view commit history and identify the commit's SHA-1 hash (its unique ID).
- **Pick the cherry:** Use the command `git cherry-pick <commit-hash>` to apply that specific commit to your current branch.
