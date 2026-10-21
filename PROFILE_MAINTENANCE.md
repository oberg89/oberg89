# Profile maintenance

The rendered profile is intentionally minimal: one typographic hero, one sentence, one typographic Angler Log project cover, one public-showcase CTA and a small LinkedIn link. No fish artwork, animals or icons.

## Assets

- `assets/banner.svg`: original, self-contained typography on charcoal. No scripts, fonts fetched over the network, embedded images or animation.
- `assets/angler-log.svg`: original typographic project cover. No fish, animals, mascots, icons or decorative illustrations. Keep the project name and short tagline readable on narrow screens.

Only these two visual assets are used. Do not reintroduce counters, badge walls, unrelated projects, dashboards, decorative UI, long biography or multiple project calls to action.

## Public boundary

Only link the public `oberg89/SportfiskeDagboken-showcase` repository. No private production repository links, private issue contents, internal addresses, infrastructure details or credentials. LinkedIn uses the contact URL already published on the GitHub account and may block automated checks with HTTP 999.

## Review

Validate the SVG as XML and render both assets. Check relative paths, alt text and GitHub README rendering on desktop and narrow screens. Run `git diff --check`. Submit changes on a branch from `main` through a PR; do not merge automatically. Merging into `main` updates the public GitHub profile without a deployment.
