# CLAUDE.md

## Mascot & banner

This repo has a pixel mascot banner at the top of the root `README.md`
(mascot: **Homie**, a little house with a heart on the door), swapped
light/dark via `.github/banner-*.svg`. See `DESIGN.md` for the rationale.
Don't regenerate or redesign it without checking there first — it's part of
a matched 12-repo set across the GattyWorks org, and a one-off restyle here
would break that consistency. This is separate from `profile/README.md`,
which is the org's public profile page and has its own existing banner —
don't touch that one as part of this.

## Workflow

Never push straight to `main`. Every change goes through a short-lived
branch and a PR.
