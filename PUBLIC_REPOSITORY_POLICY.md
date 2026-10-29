# Public Repository Policy

This community repository is public. Assume every tracked file, commit, release
asset, issue, and discussion can be read by anyone.

Public Markdown is limited to `README.md`, `CHANGELOG.md`, `CONTRIBUTING.md`,
`CODE_OF_CONDUCT.md`, `SECURITY.md`, this policy, and
`.github/PULL_REQUEST_TEMPLATE.md`. Contributor issue forms and routing
configuration belong in `.github/ISSUE_TEMPLATE/`. `LICENSE` contains the
published MIT license.

Put local plans, agent context, investigation notes, security work, and release
coordination in `.internal/`; that directory is ignored and must never be
force-added.

Never store credentials, tokens, private keys, customer data, private URLs, or
real environment values in this repository. From the canonical ZemDomu
monorepo root, run:

```sh
node scripts/check-public-repo-safety.mjs --package meta
```

If sensitive information is committed, stop publication, revoke or rotate the
affected credential, report the exposure privately, and assess Git history.
Removing the current file does not remove earlier commits; do not rewrite
shared history without an explicit coordinated decision.
