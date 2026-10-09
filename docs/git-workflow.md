\# Git Workflow Documentation



\## 1. Main Branch



The `main` branch contains the stable version of the project.



\## 2. Development Branch



The `dev` branch is used for development and integration.



\## 3. Feature Branch



Feature branches are created from `dev` to develop individual features.



Example: `feature/task-documentation`



\## 4. Pull Request Workflow



1\. Create a feature branch from `dev`.

2\. Make changes and commit them.

3\. Push the feature branch to GitHub.

4\. Create a pull request to merge the feature into `dev`.

5\. Create another pull request to merge `dev` into `main`.



\## 5. Git Tags



Git tags identify specific versions of the project.



Example: `v1.0.0`



\## 6. Common Git Commands



\* `git init` — Initialize a repository.

\* `git add` — Stage changes.

\* `git commit` — Save a snapshot.

\* `git switch` — Switch branches.

\* `git merge` — Merge branch changes.

\* `git push` — Upload commits to GitHub.

\* `git tag` — Create a version tag.



\## 7. .gitignore



The `.gitignore` file specifies files and folders Git should ignore.



