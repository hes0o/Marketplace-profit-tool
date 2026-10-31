# Contributing

Rules for working in this repo.

1. One ticket = one branch = one pull request.
2. Branch names: `p1-XX-short-name` using the step number, for example `p1-04-supabase-setup`.
3. Never push directly to `main`. Everything goes through a pull request.
4. Commit messages: short, start with a verb, present tense: `Add login page`, `Fix VAT rounding`.
5. The other person reviews within 24 hours. The author merges after approval.
6. Never commit secrets: no `.env` files, API keys, passwords or database URLs.
7. Before opening a PR, run `pnpm lint` and `pnpm typecheck` locally (these exist after step P1-02).