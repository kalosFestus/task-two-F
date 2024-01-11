# learnable-task-two

**Question 1: Explain Version Control**
Version Control also known as source control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It allows you to revert selected files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. This also means that if
you make mistakes or lose files, you can easily recover them.

**Question 2: Explain difference between git and github**
While Git and GitHub are related, they are distinct tools used in the realm of version control and collaborative software development. Such differences include the following:
- Git is a version control system that operates locally on a developer's machine. Changes and commits are tracked on the user's computer WHILE GitHub is a web-based platform that hosts Git repositories in the cloud, providing a centralized location for collaboration and code storage.
- Git allows multiple developers to work on the same codebase independently and then merge their changes WHILE GitHub adds a layer of collaboration tools on top of Git, such as pull requests, issues, and project boards, facilitating teamwork and communication.
- Git is installed on a developer's local machine, making it independent of internet connectivity. Developers can work on their code even when offline WHILE GitHub is a cloud-based platform, and to use its collaboration features, an internet connection is required. It provides a centralized location for code storage and collaboration.
- Git is primarily a version control system designed to track changes in code and manage its history WHILE
GitHub is a platform built around Git, enhancing collaboration, providing a central repository hosting service, and offering tools for project management.

In summary, Git is the version control system, while GitHub is a web-based platform that uses Git for version control and adds collaborative features to facilitate team development. Git can be used without GitHub, but GitHub leverages Git for distributed version control with additional collaboration and project management capabilities.

**Question 3: List 3 other github alternatives**
1. Gitlab
2. Bitbucket
3. SourceForge

**Question 4: Explain the difference between git fetch and git pull**
`git fetch` is primarily used to bring changes from the remote repository to your local repository without automatically merging them into your working directory.
`git pull` is used to fetch changes from the remote repository and automatically merge them into your current working branch.
In practice, if you are working on a branch and want to update it with changes from the remote repository, you might choose `git fetch` followed by `git merge` or `git pull`, depending on whether you want to review the changes before merging.

**Question 5: Explain in simple terms git rebase and the command for it**
`git rebase` is a Git command used to change the base of your current branch. It allows you to move or combine a series of commits to a different branch or a different point in your commit history.
Command for git rebase ```git rebase [base-branch]```

**Question 6:Explain in simple terms git cherry-pick and the command for it**
In simple terms, git cherry-pick is a Git command that allows you to copy specific commits from one branch and apply them onto another branch. It's like picking a cherry (commit) from one tree (branch) and placing it on another.
Command for git rebase ```git cherry-pick <commit-hash>```
