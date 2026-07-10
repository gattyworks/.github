# Design

## Mascot & banner

This repo's mascot is **Homie** — a little red-roofed cream house with a
heart on the door.

The concept: `.github` is the literal front door of the whole org — it holds
the community health files every other repo inherits and the profile GitHub
renders at github.com/gattyworks. A little house with a heart on the door is
a direct, warm metaphor for that role.

Homie is one of twelve pixel mascots across the GattyWorks org, one per
repo, each drawn from what that repo actually does rather than a shared
template. The full cast and the generator that produced these banners live
outside this repo's history; check the workspace mascot sheet if you need to
regenerate or reshape this one.

**Palette**: red roof (`#E0574F`), cream walls (`#F2E3C8`), heart accent
(`#E85D75`).

**Files**: `.github/banner-dark.svg` and `.github/banner-light.svg`, swapped
automatically in the root `README.md` via `prefers-color-scheme`. Both are
static (no animation) so they render identically wherever GitHub displays
them.

**Scope note**: this banner is for the repo's own root `README.md` only. It
is unrelated to [`profile/README.md`](profile/README.md), the org's public
profile page, which already has its own finished design (badge showcase,
adaptive light/dark LinkedIn banner) and was left untouched.
