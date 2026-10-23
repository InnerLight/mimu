# Dot Along

## Product direction

Dot Along is the working name for a small, local-only routine app with playful retro pixel creatures. Its core principle is **hands-free by default; controls are optional**.

Users run a sequence of timed tasks that advances automatically, without checking off each task or dismissing transitions. Brief cues announce the next task. Independent scheduled reminders provide a brief alert without requiring completion.

Each task automatically receives an animal or creature and a color, with customization available. Creatures show timer progress by moving along and consuming time dots, with small goofy animations. They are part of the interface, not pets to care for.

Optional controls include pause/resume, extend time, finish early and advance, skip, and remind later where applicable. Their exact behavior and scheduling consequences remain undefined.

## First milestones

1. Build a replayable built-in demo with three 10-second steps: relax shoulders (chicken), take a slow breath (whale), and stretch hands (crab).
2. One tap starts the demo; it advances and finishes without check-offs. The demo does not count toward the free task allowance.
3. Treat the foreground demo as an interaction demonstration only. Minimal placeholder art is sufficient; final animation assets are not needed to prove timing behavior.
4. Before expanding features, complete a separate early physical-device feasibility checkpoint: validate hands-free progression and brief alerts with the phone locked, plus required Apple Watch behavior once defined.

These are planned milestones, not claims of implemented or verified capabilities.

## Platform and implementation direction

- iPhone and Apple Watch support are required product goals. Starting a named routine through Siri is intended; exact Watch responsibilities and Siri implementation timing remain undecided.
- Do not promise background execution or native capabilities before validation.
- No backend service, account system, analytics, advertising, or recurring hosting service is planned.
- The implementation stack and local storage technology are not selected. SQLite is compatible with local-only operation but is not mandated.

## Later scope

- Tasks that require checking off.
- Reusable grocery lists with reset behavior.
- A standalone one-off timer.

“Like Reminders” does not promise all Apple Reminders features. Do not inherit Show Up, Goal tiers, construction, or reward mechanics from previous projects, or copy their architecture or product rules.

## Business direction

A free tier is planned with a task limit and starter creatures. A one-time purchase would unlock more tasks and all creatures; no subscription is planned. Three free tasks is proposed, but whether the limit is total or per routine remains undecided. $7.99 is tentative, not a finalized price. Payment infrastructure is outside the first milestone.

## Open decisions

- Fixed clock-time starts versus sequential durations; gaps and overlaps.
- Whether extending, pausing, skipping, or finishing early shifts later tasks.
- Late starts, missed cues, app termination, and restart behavior.
- Exact cue format, notification behavior, and Watch responsibilities.
- Exact optional-control behavior and Siri implementation timing.
- Free-tier counting and final price.

## Purpose

Build a useful personal product with possible modest commercial value, develop mobile engineering and disciplined AI-assisted development skills, and maintain an employer-facing portfolio that honestly distinguishes planned, implemented, and verified capabilities.
