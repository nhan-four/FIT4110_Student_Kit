# Git guide — one semester repository

Create one empty **public** GitHub repository once: `FIT4110_<MãSinhViên>`. Clone it locally, then keep every lab in a separate folder. Example layout:

```text
FIT4110_<MãSinhViên>/
├── 01_Setup/
├── 02_OpenAPI/
├── 03_Postman/
├── 04_Docker/
├── 05_Compose/
└── 06_Plugathon/
```

For each source lab, clone it separately, complete its work, then copy its contents into the matching folder above **without its `.git` directory**. From the portfolio repository:

```bash
git status
git add .
git commit -m "lab03: add contract tests and evidence"
git push -u origin main
```

Set `origin` only once, when you create the portfolio repository: `https://github.com/<your-account>/FIT4110_<MãSinhViên>.git`. Verify with `git remote -v`, then refresh GitHub and inspect folders, commit history, and visibility.

Use small, meaningful commits: `docs: define service boundary`; `contract: sign OpenAPI v1`; `test: add invalid payload cases`; `docker: package service`. Do not commit `.env`, tokens, private datasets, or giant generated dependency folders.

If you must preserve upstream updates, add it explicitly: `git remote add upstream <public-source-URL>`; never push to `upstream`.
