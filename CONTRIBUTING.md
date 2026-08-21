# Contributing to Ottom-OS

This document is the default contribution doctrine for every Ottom-OS repo unless a repo overrides it locally.

## The short version

1. **Open an issue first.** Drive-by PRs without an issue get closed without review.
2. **Fill the template.** Incomplete templates get auto-labeled `needs-info` and ignored until completed.
3. **One PR = one idea.** Bundled PRs get sent back.
4. **Proof over promises.** If your PR touches a skill or automation, include telemetry, test runs, or a link to a production incident it solved.

## The rules

### Issues

- Use the provided templates. Blank issues are auto-closed by CI.
- Search first. Duplicates get linked and closed.
- One issue = one problem. Don't bundle.
- Security issues go to **SECURITY.md** process, NOT public issues.

### Pull requests

- **Reference the issue.** `Closes #NNN` in the description. No issue = no merge.
- **Fill the PR template completely.** Sections left blank block review.
- **CI must be green.** No exceptions, no "it's flaky" — if CI is flaky, that's a separate issue.
- **Sign your commits.** DCO sign-off (`Signed-off-by:` line) or GPG.
- **Small > big.** A 50-line PR gets reviewed today. A 500-line PR gets reviewed eventually.
- **Tests or it didn't happen.** New behavior without tests gets sent back.

### Code style

- Match the file you're editing. Don't reformat code you didn't touch.
- No debug prints in committed code.
- No commented-out dead code.
- Secrets never touch the repo. If you accidentally commit one, open a security issue immediately — rotation is a drill we practice.

### Conduct

- Be direct. Be kind. Both at once.
- Assume good faith. Call out bad behavior privately first.
- Maintainers have final say. Respect the call, fork if you must.

## Recognition

Merged PRs earn reputation in the Foundry ledger:

- PR merged → +N reputation (N set by difficulty label)
- Issue accepted → +1
- Security report validated → +10

Reputation has real protocol advantages: priority review, lower Foundry fees, early access to new primitives.

## The bad guy

Our CI is the draconian one. It auto-labels, auto-closes, auto-rejects. Our human maintainers get to be the nice ones. Don't take the bot's behavior personally — it's the design.

## Questions

Open a discussion. Don't email maintainers directly unless it's a security issue.
