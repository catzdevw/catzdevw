# catzDev profile — maintenance guide

The profile at [github.com/catzdevw](https://github.com/catzdevw) is driven by the root `README.md` in this special repository.

## Files in use

- `README.md` — introduction, expandable tech-stack sections, architecture explanation, project case studies, activity, and links.
- `assets/banner-dark.svg` and `assets/banner-light.svg` — complementary catzDev hero banners, selected based on the visitor's GitHub theme.
- `assets/architecture.svg` — black-violet full-stack systems diagram.
- `assets/divider.svg` — section dividers.

Other images in `assets/` are preserved from earlier iterations but are not presently referenced by the README.

## Maintaining accuracy

- Primary stack: Java, Spring Boot, React, TypeScript, PostgreSQL.
- Avoid unsupported experience levels, invented achievements, fake production claims, or unverifiable statistics.
- Project descriptions are case studies: the source repos may be private or owned by collaborators. If a project becomes public, optionally add its exact public URL.
- Do not publish private repository names, source details, emails, or personal contact details without deciding to make them public.
- Update the stack and work sections as verified experience changes.

## Interactivity and constraints

GitHub profile README pages support Markdown, compatible HTML such as `<details>`/`<summary>`, clickable links, SVG imagery, and third-party image-based activity services. They do not support arbitrary JavaScript applications or custom CSS.

Banner cursor animation is SVG-native, with a readable static fallback. Live typing/stats/contribution images rely on third-party providers, so images may be cached, limited, or temporarily unavailable.

## How to update

Edit `README.md` on the `main` branch, or submit a pull request. GitHub will automatically render the updated profile README.

Keep headlines concise, ensure badges and diagrams have useful alternative text, and verify links after edits.
