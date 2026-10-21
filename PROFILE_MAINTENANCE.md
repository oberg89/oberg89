# Profile maintenance

This repository is the public GitHub Profile README for `oberg89`. The design uses only GitHub-compatible Markdown/HTML and local SVG files. No build, web server, GitHub Actions or third-party graphics service is required.

## Update content

- Edit `README.md` and the relevant SVG directly. Keep project descriptions general when source code is private. Never add private repository links, issue content, hostnames, network addresses, credentials or runtime details.
- SportfiskeDagboken links only to the public `SportfiskeDagboken-showcase` repository. The showcase is a deliberately limited portfolio example, not the production application.
- WYSPIR TECH links to its public website. Home Assistant Ops and Unraid Ops have deliberately unlinked project cards.
- The thirteen technology badges use original, consistent line artwork and text labels; they are not official vendor logos.

## Refresh statistics

`assets/github-stats.svg`, its alternative text and the matching README caption are a static public snapshot dated 2026-10-21. They show 10 public repositories and 4 followers. Verify fresh values with GitHub's public API before changing the numbers; update the date in the SVG, its description and the README together. Do not infer private contributions or publish private repository counts. The public links remain the source for current activity.

## Verify before publishing

1. Parse every SVG as XML. Keep SVGs self-contained: no JavaScript, foreignObject, external fonts, external images, remote stylesheets or event handlers.
2. Render the banner, all cards and badges. Check the README at desktop and mobile widths. Images scale down; badges wrap naturally. Markdown headings and descriptive alternative text preserve the meaning when images are unavailable.
3. Verify relative asset paths and public destination links. LinkedIn can block automated checks with HTTP 999; verify it manually if needed.
4. Run `git diff --check`. Review changes for confidential information.
5. Publish through a feature branch and PR. Merging the PR into `main` updates the public profile; there is no deployment step.
