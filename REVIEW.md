# REVIEW.md

## What this repo is

A small collection of OpenClaw skills (`skills/<name>/SKILL.md`), published openly. Currently one skill directory (`market-intelligence`) plus `README.md` and `LICENSE`.
No CI, build, lint or test configuration was found in the repo.

## Review priorities (in order)

1. Correctness: each skill is a directory with a `SKILL.md`; instructions must be accurate and internally consistent with the README skill table.
2. Security and privacy: no secrets, tokens, personal data or private endpoints in skills or examples.
3. Repo-specific invariants: not determined from the repo (no AGENTS.md, CLAUDE.md or CONTRIBUTING found). Keep the README table and installation commands in sync with `skills/`.

## Sensitive paths

Not determined from the repo (no workflows, hooks or install scripts found). Treat any future `.github/**` and any script a skill asks the agent to run as sensitive.

## What NOT to flag

Formatting or wording style: no linter or formatter config found.

## How to verify

No automated command exists in the repo. Check by reading: frontmatter of each `SKILL.md` is valid YAML, and README entries match `ls skills/`.
