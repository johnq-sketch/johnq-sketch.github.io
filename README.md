# Site Structure

This site is now organized around section folders and project-owned folders, not a flat root of public pages plus a separate asset tree.

## Public entry pages

- `home/home.html`
- `projects/index.html`
- `ventures/index.html`
- `writings/writing.html`
- `index/collections.html`
- `contact/contact.html`
- `now/now.html`

## Shared resources

- Global styles and shared files live under `global/`
- Current shared stylesheet path: `global/css/style.css`

## Projects structure

`projects/` is both the public projects section and the working directory for project materials.

- `projects/index.html` is the public landing page
- `projects/Selected Works/`
- `projects/Case Archive/`
- `projects/Research Archive/`

Each project should, whenever possible, own its own folder rather than only a single loose html file.

### Folder naming rule

Use a category prefix plus project name plus year or status:

- `R - Nepal - 2024`
- `C - DIC - 2025`
- `V - bendi - now`

Where:

- `R` = research
- `C` = case
- `V` = venture

### What belongs inside a project folder

Keep the page and its working materials together:

- the public html page
- images used by the page
- PDFs
- PPTX / DOCX / Rmd / notes
- future source materials and draft assets

Do not split public page files into one place and source materials into an unrelated generic asset tree if the project already has its own folder.

## Ventures structure

`ventures/` follows the same folder-owned logic:

- `ventures/index.html` is the public ventures landing page
- each venture should live in its own folder when materials exist

## Editing rules

- Treat navigation as shared UI and keep it synchronized across all public entry pages and detail pages.
- Keep links aligned with the current folder structure. Do not leave old `projects.html` / `research.html` style paths after moving files.
- When a project moves into a dedicated folder, update all related dropdowns, landing pages, and entry links in the same pass.
- If a page no longer exists, remove the link rather than leaving a broken target.
- Do not replace public pages with redirect shells unless explicitly requested.
- Research and case detail pages should meet the richer standard already established by the stronger project pages, not remain as thin placeholders once materials exist.

## Writing and tone

- Follow `介绍词写作规则.md` when rewriting project introductions.
- Avoid generic grouping copy under section headers unless explicitly requested.

## Travel archive

Travel media currently lives under `index/places/`.

Prefer compressed images and web-optimized formats when possible.
