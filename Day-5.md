---

---

--- Before Day-5 ---
I had heard about Git and GitHub and had used GitHub to download code repositories before. However, I did not fully understand version control, commits, staging, branching, SSH authentication, or how local repositories are connected to remote repositories on GitHub.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Day-5 Checklist

* [x] I understand what Git is and why version control systems are useful
* [x] I can explain the difference between Git and GitHub
* [x] I have Git installed and configured with my username and email
* [x] I know how to generate an SSH key and connect it to GitHub
* [x] I know why the default branch is usually named `main`
* [x] I can initialize a repository using `git init`
* [x] I understand the purpose of the hidden `.git` directory
* [x] I can create and use a `.gitignore` file
* [x] I know why virtual environments and `.env` files should not be committed to GitHub
* [x] I understand the purpose of `.env.example`
* [x] I can check repository status using `git status`
* [x] I can stage files using `git add`
* [x] I understand the difference between `git add .` and staging specific files
* [x] I can create commits using `git commit -m`
* [x] I can inspect changes using VS Code's diff view
* [x] I understand what a commit snapshot represents
* [x] I can connect a local repository to GitHub using `git remote add origin`
* [x] I understand how Git helps track code changes and roll back to previous versions
* [x] I know the basic workflow: edit → stage → commit → push

--- After Day-5 ---
I learned how Git tracks changes in a project without requiring multiple copies of files. I learned how commits act as snapshots of a codebase, how staging works before committing changes, and how GitHub can be used as a remote repository. I also learned how to use SSH keys for authentication, why `.gitignore` is important for security, and how version control helps when code must be updated or rolled back due to changes in external APIs or software dependencies.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

--- Feedback (Suggestions for the TDS Team) ---
The real-world examples showing how API schema changes can break existing code helped explain why version control is important. The demonstrations of staging, commits, diff views, and rollback concepts were particularly useful. A short hands-on exercise where every participant creates a repository, makes multiple commits, and performs a rollback would make the concepts even clearer.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

---

---

Personal Notes:

* Git is a distributed version control system created by Linus Torvalds.
* GitHub is a platform that hosts Git repositories remotely.
* `git init` creates a hidden `.git` folder that stores repository metadata.
* `git status` shows tracked, modified, and staged files.
* `git add` moves changes to the staging area.
* `git commit -m "message"` creates a snapshot of the current staged changes.
* `.gitignore` prevents unnecessary or sensitive files from being tracked.
* `.env` files should be ignored because they may contain secrets.
* `.env.example` can be shared publicly as a template.
* Diff view helps compare changes between versions.
* Git enables reverting to previous working versions of code.
* SSH authentication is generally preferred over passwords for GitHub operations.
