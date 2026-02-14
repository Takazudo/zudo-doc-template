# zudo-doc-template

A template repository for creating documentation sites with [Docusaurus](https://docusaurus.io/).

## What's Included

- **Docusaurus 3.x** with TypeScript and the classic preset
- **Custom styles** - Orange oklch color palette, Noto Sans JP font, refined typography and sidebar styling
- **Two-column landing page** - Sticky sidebar with title/logo/links + expandable docs sitemap
- **Document metadata** - Creation date, last updated date, and author displayed under h1 titles (from git history)
- **CategoryNav component** - Auto-generated navigation lists on category index pages
- **DocsSitemap component** - Boxed accordion-style sitemap with all sidebar entries
- **Build-time data generation** - Scripts that scan markdown files and produce JSON data for components

## Usage

Clone this repository and start building your documentation:

```bash
cd doc
pnpm install
pnpm start
```

## Structure

```
doc/            # Docusaurus site
  docs/         # Documentation content (markdown)
    inbox/      # INBOX category
    top-category-1/
    top-category-2/
    top-category-3/
```

See [doc/README.md](doc/README.md) for detailed development instructions.
