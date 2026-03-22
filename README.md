## Explain version control

Version control is a system that acts like a "time machine" for your project files, allowing you to track changes, see who made them, and revert to any previous state if something goes wrong. It allows multiple people to work on the same project simultaneously without overwriting each other's work.

## Explain difference between git and github

• **Git:** The engine—a local software tool that tracks changes to your code on your own computer. It works offline and handles the actual versioning (snapshots, branching, and merging).

• **GitHub:** The garage—a cloud-based platform that hosts Git repositories. It adds a social and collaborative layer, allowing you to share code with others, manage tasks, and back up your work online.

## List 3 other github alternatives

1. **GitLab:** A comprehensive "all-in-one" DevOps platform with advanced built-in tools for security and automated testing.
2. **Bitbucket:** Best for teams already using the Atlassian ecosystem (like Jira and Trello) for project management.
3. **Gitea:** A lightweight, fast, and simple open-source option that is easy to self-host on your own server.

## Explain the difference between git fetch and git pull

• **Git fetch:** Only "looks" at what’s new. It downloads the latest changes from the remote server but does not change your current files. It’s safe because it lets you review code before you decide to merge it.

• **Git pull:** "Grabs and integrates" the changes. It is essentially two commands in one: git fetch followed immediately by git merge. It updates your local files right away, which can sometimes lead to conflicts.

## Explain in simple terms git rebase and the command for it

Rewrites History: It takes all the work you've done on your branch and "replays" it on top of the latest version of another branch, making the project history look like a single straight line.

_git rebase <branch_name>_

## Explain in simple terms git cherry-pick and the command for it

Selects Specific Work: It allows you to pick one specific "save point" (commit) from a different branch and apply just those changes to your current branch without merging everything else.

_git cherry-pick <commit_hash>_
