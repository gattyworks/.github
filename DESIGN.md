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

**Files**: `design/banner.svg` is the README banner. It is project-themed —
the colors and the facts on it come from this repo itself, not from a shared
org template — and the mascot is one element of it, not the whole banner.
`design/banner.html` is a self-contained reference page showing the banner
plus the theme tokens it was built from. Referenced from `README.md` by a
plain relative `<img src>` (works for public repos too and keeps the
reference portable). The old `.github/banner-*.svg` files are removed.

**Scope note**: this banner is for the repo's own root `README.md` only. It
is unrelated to [`profile/README.md`](profile/README.md), the org's public
profile page, which already has its own finished design (badge showcase,
adaptive light/dark LinkedIn banner) and was left untouched.
