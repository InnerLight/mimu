# Working on Dot Along

## Context and scope

- Read `PROJECT.md` and relevant existing code before making changes. Treat `README.md` as the public introduction and `PROJECT.md` as current product direction.
- Do not invent unresolved product behavior. Surface decisions when they become necessary.
- Make small, bounded changes with clear acceptance criteria. Explain the approach and important tradeoffs in plain language.
- Support the developer's learning: explain meaningful code changes and provide brief review questions when useful.
- Do not add dependencies or select or change the stack without approval.

## Implementation and verification

- Keep timer behavior independently testable and separate from creature animation and screen rendering.
- Do not assume repeating JavaScript intervals run continuously while iOS is suspended.
- Use the narrowest relevant verification for each change. Do not add meaningless tests or claim unrun checks passed.
- Physical-device claims require actual device verification. Label planned, implemented, and verified behavior accurately.

## Preservation and privacy

- Preserve existing work. Do not stage, commit, push, delete existing work, or run destructive Git commands without explicit authorization.
- Do not put personal details, credentials, tokens, signing materials, or private local paths in committed documentation.
- Do not copy code or assets from other apps without appropriate rights. Do not import architecture or product rules from archived companion projects.

## Reporting

Final reports must state files changed, verification performed and its results, unresolved issues, and complete `git status --short` output.
