# Portfolio Project Guidelines

## Project structure
- This is a Jekyll site published at `hanifrizki.github.io`, using the Minimal Mistakes remote theme and `jekyll-include-cache`.
- Site settings, author details, page defaults, and main navigation are in `_config.yml`.
- Content is primarily Markdown: `index.md` is the About page; `research.md`, `cv.md`, and `projects.md` are standalone pages; `notes/` contains public Obsidian notes.

## Editing conventions
- Preserve existing YAML front matter and page metadata when editing Markdown pages. Follow the page's existing `layout`, `title`, and `permalink` conventions.
- Keep navigation changes consistent with the `navigation.main` entries and page permalinks in `_config.yml`.
- Preserve Obsidian wikilinks in notes unless the task specifically concerns converting or changing them.
- Keep academic and biographical content faithful to the source; do not invent qualifications, research results, links, or personal details.
- Keep changes focused. Do not introduce a new framework, build system, or dependency for a content or styling change without a clear need.

## Validation
- Check the rendered page and relevant Jekyll configuration after content or navigation changes.
- Before suggesting build or test commands, check the repository for its current scripts and workflows; do not assume a local test suite or add one for a content-only change.
