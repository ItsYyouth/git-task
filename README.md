# TASK ON GIT AND GITHUB

## What is Version Control?
Version control, also known as source control, is the practice of tracking 
and managing changes to software code.
It is a system that tracks changes to files over time, allowing a developer to 
revert to previous versions, Collaborate with others without overwriting each other's work 
and understand the history of changes.

---

## Difference Between Git and GitHub
 Git is a version control system that lets you manage and keep 
 track of your source code history while GitHub is a cloud-based 
 hosting service that lets you manage Git repositories

### Git:
- **Type**: A version control system.
- **Function**: Manages and tracks changes in source code.
- **Where It Runs**: Locally on your computer.
- **Key Commands**: `git init`, `git commit`, `git branch`, `git merge`.

### GitHub:
- **Type**: A cloud-based platform.
- **Function**: Hosts repositories and facilitates collaboration.
- **Where It Runs**: Online.
- **Key Features**: Pull and push requests, issue tracking, and repository hosting.

---

## Alternatives to GitHub
1. **GitLab**: Known for DevOps integration and CI/CD tools.
2. **Bitbucket**: Ideal for teams using Atlassian tools like Jira.
3. **SourceForge**: Popular for hosting open-source projects.

---

## Difference Between `git fetch` and `git pull`

### `git fetch`
- Downloads updates (commits, branches, tags) from the remote 
repository but **does not merge them** into the local branch.

### `git pull`
Combines git fetch and a merge operation, updating the local 
branch with the latest changes from the remote repository.

## What is Git Rebase?
Git rebase is a way to reapply commits on top of another branch, 
effectively creating a linear history. It moves your branch to the 
tip of the base branch, making the commit history cleaner.

- command: git rebase <base-branch>

## Git Cherry-Pick?
Git cherry-pick is used to apply specific commits from one branch to 
another. It’s useful when you only want to pick certain changes without 
merging the entire branch.

- command: git cherry-pick <commit-hash>
