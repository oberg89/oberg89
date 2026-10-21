# Profile maintenance

The profile uses GitHub-compatible Markdown and HTML: a centred text header, a brief About Me, a two-column technology table, one Angler Log project, and LinkedIn. No custom CSS, hero images, illustrations, animals, stats, tracking widgets, or external image services.

## Badges

The eleven small SVG badges in assets/ share one navy/cyan style. They are local, self-contained text labels with no scripts, embedded images, fonts, or network dependencies. Reuse badges rather than adding duplicate technologies. Keep table rows narrow and check at 320px.

## Public boundary

Only link the public SportfiskeDagboken-showcase repository and the existing LinkedIn profile. Do not publish private repository links, implementation details, credentials, or internal addresses. Project technology labels must be supported by the public showcase.

## Review

Parse every SVG as XML, reject unsafe content, check nonempty files and relative paths, and inspect actual GitHub rendering at desktop and mobile widths. Run git diff --check. Deliver changes on a feature branch through a PR without automatic merge. The public profile updates when the PR is merged into main.
