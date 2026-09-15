# AI / Coding Agent Operating Rules

Before making any change in this repository, read `.chatgpt/PROJECT_CONTROL.md`.

Mandatory rules:
1. Confirm the repository identity and project scope before editing.
2. Never mix files, domains, analytics IDs, deployment settings, or requirements from another project.
3. Inspect the current repository state before changing code.
4. Prefer the smallest safe change that solves the stated problem.
5. Preserve working functionality unless the user explicitly asks to replace it.
6. Never claim a fix is live until the deployment and production URL are verified.
7. If a deployment, DNS, analytics, or hosting fact is marked unverified, verify it instead of guessing.
8. After a change, check for regressions relevant to the change.
9. Treat `.chatgpt/PROJECT_CONTROL.md` as the canonical project identity file.
10. "Done" means: change committed, deployment status checked when applicable, production behavior verified when applicable, and no known regression introduced.
