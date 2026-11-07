# Contributing to Lightcone Studios repositories

Thanks for working with us. These defaults apply to every repository in the organization unless a repository's own docs say otherwise.

## The short version

1. **Never commit to the default branch.** It is enforced by an organization ruleset: all changes arrive by pull request, force pushes and deletions are blocked, no exceptions and no bypass.
2. **Branch names:** `feature/`, `fix/`, `chore/`, or `docs/` plus a short kebab-case slug.
3. **Commits:** one logical change per commit, Conventional Commits style (`fix:`, `feat:`, `docs:`, `chore:`). Each commit should pass tests on its own.
4. **Pull requests:** small enough to review in one sitting, ideally under 200 changed lines. Fill in the Captain's Card template completely. The **Proof** field is not optional: show the test run, the command output, or the verification you performed.
5. **Secrets:** never commit tokens, keys, credentials, or `.env` files. If you spot one in history, stop and report it privately (see SECURITY.md) rather than opening a public issue.
6. **Review rails:** every PR is classified GREEN (routine, reversible), AMBER (needs a judgment call), or RED (security-adjacent, requires the owner's eyes on the diff). When unsure, call it AMBER and say why.

## Working standards

- Verify before you claim. "Done" means the verification ran and passed, with the output in the PR.
- State your hypothesis before debugging, and change one variable at a time.
- Prefer the 3-line targeted fix over the rewrite.
- Refactors and behavior changes ship as separate PRs.
- If you are stuck, say so in the PR rather than pushing speculative fixes.

## Account expectations

Collaborators are expected to have two-factor authentication enabled on their GitHub account.
