# CLAUDE.md

GitHub profile README of Junaid Ahmed. `README.md` is what github.com/junaidahmed501 shows; nothing else in this repo is rendered.

## README.md is generated

- **Don't edit `README.md` here.** It is generated from `profile/data.ts` in `junaidahmed501/junaidahmed.dev` (template: `readme()` in `profile/render.ts`), published at https://junaidahmed.dev/readme.md, and pulled into this repo by `.github/workflows/sync-readme.yml` every hour. A hand edit is overwritten by the next run.
- To change the text, change the facts or the template in the website repo and deploy it. To pull right away: Actions tab, "Sync README", Run workflow.
- The job only accepts a file whose first line is the generated marker comment, so a broken deploy can't blank the profile.
- GitHub turns off scheduled workflows in a repo with no activity for 60 days. If `pnpm sync` in the website repo reports the README as stale, re-enable the workflow in the Actions tab.

## Rules

- **Only skills used in real work.** Enforced at the source: `pnpm build` in the website repo checks the generated README.
- **No phone number.** Contact routes are email, the website, LinkedIn and the Calendly link.
- No em dashes. No flattery. Sentence case headings.
- No Claude attribution in commits or in the README. The sync job commits as `github-actions[bot]`.

## Git workflow

For changes to the workflow or this file:

- `master` is live: GitHub shows it on the profile as soon as it is pushed.
- One working branch at a time, named after the change.
- When it is done: fast-forward or squash it into an up-to-date `master`, push, then delete the branch on GitHub and locally.
- No pull requests. Before starting a branch, check that no other working branch is left over; if one is, finish or delete it first.
- Commit as `junaid <junaidahmed501@gmail.com>`.
