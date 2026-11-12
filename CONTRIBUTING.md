# Contributing — RaDe Digital

- Create new repositories from [`radedigital/repo-template`](https://github.com/radedigital/repo-template).
- Never push or commit directly to `main`.
- Always work on a branch named `feat/…`, `fix/…`, or `chore/…`, and open a pull request into `main`.
- The `ci` check must pass before merging.
- At least one review/approval is required from someone other than the pull request author before merging.
- Do not commit secrets or `.env` files. `.env.example` (with no secrets) is fine.
- Do not commit `node_modules` or build output (`dist/` and similar).
- Production deploys need Raja's explicit approval.
- Follow GDPR basics: no personal data in code, logs, or fixtures.
