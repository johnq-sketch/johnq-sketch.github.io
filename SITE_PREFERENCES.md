# Personal Site Preferences

This file records stable preferences established during recent edits to the personal website, so future changes stay aligned with the intended tone, structure, and presentation.

## Overall Direction

- The site should feel minimal, intentional, and personal, not like a generic portfolio template.
- Keep the current black background, white text, and restrained gold accent system unless explicitly changed.
- The visual tone should be clean and cinematic rather than decorative.
- Prefer calm hierarchy and whitespace over dense information blocks.

## Typography

- Avoid making the site feel busy through typography.
- Large display text is acceptable on the home page, but supporting text should stay restrained.
- Chinese long-form text should remain readable, with moderate line height and spacing.
- Titles for research/project content should generally lean Chinese and academic in tone.
- Avoid unnecessary mixed-language styling unless there is a clear reason.

## Branding And Navigation

- The site name in the top-left navigation is `Zhanyi Qi`.
- Home hero title is `Zhanyi's Portfolio`.
- Navigation labels should stay simple and consistent across all pages.
- Shared navigation changes must be synchronized across all root pages and relevant detail pages.
- If a section is hidden, simplified, renamed, or marked unfinished, related dropdowns and entry points must also be updated.

## Current Site Structure

- `Home` remains the landing page.
- `Ventures` stays separate and should not be merged into `Projects`.
- Public entry pages now live in section folders, not at the repo root:
  - `home/home.html`
  - `projects/index.html`
  - `ventures/index.html`
  - `writings/writing.html`
  - `index/collections.html`
  - `contact/contact.html`
- `Projects` is organized as:
  - `Selected Works`
  - `Case Archive`
  - `Research Archive`
- `Writings` is currently unfinished and should show `Coming soon`.
- `Now` is hidden from navigation but the local file remains.

## Folder Ownership Rules

- File management should follow the project-folder model used in `我/`.
- New research, case, and venture pages should default to owning their own folders.
- A project folder should contain the public html page together with images, PDFs, PPTX, DOCX, Rmd, and other working materials whenever possible.
- Do not default back to the old pattern where html files live in one flat place and source files live in a disconnected generic asset directory.
- Use the current naming convention:
  - `R - ... - YEAR`
  - `C - ... - YEAR`
  - `V - ... - STATUS`
- Keep `projects/Selected Works/`, `projects/Case Archive/`, and `projects/Research Archive/` aligned with the actual location of files.

## Dropdown Behavior

- `Projects` dropdown should use grouped navigation, not a single long flat list.
- Current preferred behavior:
  - first level shows `Selected Works`, `Case Archive`, and `Research Archive`
  - hovering a group reveals project links
  - submenu should remain stable and usable, not disappear immediately on hover transition
  - submenu currently opens to the left

## Home Page Preferences

- The home page should not feel cluttered.
- The hero should rely on the large title rather than too much supporting copy.
- The intro section below the hero should feel poster-like but not overdesigned.
- Image masking should preserve image content; blending should come from added black space and soft transitions, not heavy cropping.
- Chinese introduction copy should remain the primary self-description on the page.

## Contact Page Preferences

- Contact should be minimal and centered in the viewport.
- The page should feel balanced vertically and should not rely on scrolling.
- Yellow should be used selectively for structural emphasis, not for detailed contact info.
- Specific contact values like email, WeChat, and phone numbers should stay smaller and in normal text color.
- Current preferred invitation line:
  - `欢迎任何有趣的故事和未完的计划。`

## Projects Page Preferences

- `Projects` should read more like a curated portfolio index than a database.
- The page should feel loose, readable, and sectioned rather than compressed.
- `Selected Works` should foreground the most representative work.
- `Case Archive` should appear before `Research Archive` in both dropdown navigation and page section order.
- Avoid explanatory helper text under `Selected Works`, `Case Archive`, and `Research Archive` headers unless explicitly requested.
- Page grouping should reflect the actual folder grouping rather than an outdated content taxonomy.

## Research And Case Detail Standards

- Every `research` or `case` detail page should be built to the same standard as `projects/richter.html` or `projects/todaiji.html`.
- That means the page should not remain a placeholder card with one short paragraph if source materials exist.
- Expected baseline:
  - a fully designed detail layout rather than a bare archive note
  - a substantial Chinese title with academic or analytic tone
  - a clear subtitle or source line
  - long-form explanatory prose with real argument, context, and stakes
  - page-specific assets and supporting materials when available
- DIC, MCM, and similar competition pages should be treated as full case pages, not as simple holding pages.

## Index / Destinations Preferences

- The `Destinations` tab is meant to show a meaningful travel geography, not a raw GPS log.
- Do not list nearby US or China cities separately unless they are clearly distinct, especially in cases where they belong to the same lived area or travel cluster.
- Prefer representative destinations over overly specific suburban or adjacent locations.
- For image selection:
  - avoid indoor photos when possible
  - prefer natural scenery, cityscape, or culturally legible landscape
  - avoid images that feel like generic personal snapshots with weak geographic identity
- Other countries should appear before `China` and `United States` in the current ordering.

## Image Performance Preferences

- Web images should be compressed to web-friendly sizes rather than using original full-resolution photos.
- If a page feels slow, optimize image assets before rewriting layout.

## Editing Rules

- Preserve established patterns unless the user explicitly asks for a directional redesign.
- When a change affects shared UI, update all relevant pages together.
- Prefer clear, high-signal edits over adding decorative complexity.
- When links are changed to match a new folder structure, verify the whole path graph, not just the page being edited.
