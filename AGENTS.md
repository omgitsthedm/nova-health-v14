# AGENTS.md — Nova Health V14

## Scope

- Work only inside `/Users/davidmarsh/Desktop/LiFi NYC/Clients/Nova Health/nova-health-v14` (resolved Git root: `/Users/davidmarsh/Code/LiFi NYC/Clients/Nova Health/nova-health-v14`).
- Preserve unrelated changes and inspect `git status --short` before edits.

## Source of truth

- GitHub: https://github.com/omgitsthedm/nova-health-v14.git
- Canonical branch: `master`
- Read `SOURCE_OF_TRUTH.md` for production linkage. Do not infer that Git and production are synchronized.

## Stack and commands

- Stack: Repository-specific; inspect README and manifests
- Dev: no standard development command detected; inspect the README
- Build: no standard build command detected; inspect the README
- Test: no standard test command detected
- Lint: no standard lint command detected

## Constraints

- Never expose or modify secrets, `.env*`, credentials, production data, DNS, billing, auth, payments, bookings, or real form submissions outside the requested scope.
- Clear, scoped plain-language authorization is sufficient for live changes; evaluate the user's meaning rather than matching fixed wording.
- Treat host links and historical handoffs as snapshots until verified.

## Validation and handoff

- Run the smallest relevant build, lint, test, and browser checks supported by the repository.
- Record changed files, validation, unresolved risks, and one next action. Do not paste transcripts or repeat global instructions.
