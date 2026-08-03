# Git guide — from course starter to your repository

After completing a lab locally, create an empty **public** personal repository in GitHub. From the cloned lab folder:

```bash
git status
git add .
git commit -m "lab03: add contract tests and evidence"
git branch -M main
git remote -v
git remote set-url origin https://github.com/<your-account>/<your-lab-repo>.git
git push -u origin main
```

If `origin` does not exist, use `git remote add origin <URL>` instead. Verify with `git remote -v`, then refresh GitHub and inspect files, commit history, and visibility.

Use small, meaningful commits: `docs: define service boundary`; `contract: sign OpenAPI v1`; `test: add invalid payload cases`; `docker: package service`. Do not commit `.env`, tokens, private datasets, or giant generated dependency folders.

If you must preserve upstream updates, add it explicitly: `git remote add upstream <public-source-URL>`; never push to `upstream`.
