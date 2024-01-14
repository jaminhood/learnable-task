# Git & Github

## What is Version Control?

Version control is like a time machine for your files. It tracks changes, lets you rewind to earlier versions, and helps multiple people work together without chaos. This means safer backups, smoother collaboration, and easier bug tracking, making it a must-have for any project!

Imagine your work as a cherry tree, each commit a delicious fruit. Version control lets you pick any cherry without shaking the whole branch. You can travel back in time, taste past versions, and even share your harvest with others, merging flavors without getting tangled.

This matters because it protects your work from bugs and blunders, makes collaboration smooth, and tracks the project's sweet evolution. In a nutshell, version control is a time machine, safety net, and roadmap for your creative endeavors, ensuring you always have the tastiest version on hand.

### Types of Version Control Systems

- Local Version Control Systems (VCS).
- Centralized Version Control Systems (CVCS).
- Distributed Version Control Systems (DVCS).

By a wide margin, the most popular version control system (VCS) is Git. It's estimated to be used by over 70% of developers worldwide, making it the dominant force in the field.

## What is the difference between Git and Github?

Git is your local code time machine, letting you track changes and rewind. GitHub is the online bookshelf where you store those versions, collaborate with others, and share your coding adventures!

## Some other Github Alternatives

- GitLab.
- Bitbucket.
- Codeberg.

## Difference between `git fetch` and `git pull`

- **git fetch:** Downloads the latest changes from the remote repository to your local repository without merging them into your current branch. This means you have access to the updates, but your working directory and current branch remain unchanged.
- **git pull:** Is essentially a shorthand for `git fetch` followed by `git merge.` It downloads the latest changes from the remote repository and attempts to merge them into your current branch. If the merge is successful, your working directory is updated with the combined changes. However, if there are conflicts between local and remote changes, you'll need to resolve them manually before continuing.

## `git rebase`

Imagine your Git history as a row of flower pots, each representing a commit. Rebase is like rearranging those pots to create a neater, more organized garden path.

Here's how it works:

- **Pick the starting point:** You choose the pot (commit) where you want to plant your new branch.
- **Uproot your branch:** Rebase carefully lifts your branch's pots (commits) off the ground, keeping their flowers (changes) intact.
- **Prepare the new soil:** Rebase clears the path to the chosen starting point, removing any existing pots there.
- **Replant your branch:** Rebase gently sets your branch's pots back down, one by one, in a straight line from the starting point.

The command for git rebase is: `git rebase <base-branch>`

## `git cherry-pick`

Imagine a cherry tree full of commits (changes). Cherry-pick lets you pluck a specific, delicious commit from one branch and place it on another branch, without bringing along the entire branch history.

Here's how it works:

- **Find the commit you want:** Use `git log` to view commit history and identify the commit's SHA-1 hash (its unique ID).
- **Pick the cherry:** Use the command `git cherry-pick <commit-hash>` to apply that specific commit to your current branch.
