# Documentation Guidelines

This directory hosts Markdown documents for the project. Follow these guidelines to keep the content organized and consistent.

## Directory structure
- Organize content into nested directories based on topic (e.g. `tutorials/`, `reference/`).
- Each directory may contain an `index.md` that introduces its contents.
- Prefer interlinking documents using relative links instead of copying content between files.

## Frontmatter
- Every Markdown document must start with YAML frontmatter.
- Use the following fields in this order:
  - `title`: A concise page title.
  - `description`: One or two sentence summary.
  - `tags`: A list of relevant tags.
  - `updated`: ISO 8601 date of last update (YYYY-MM-DD).
- Additional optional fields (`category`, `related`, etc.) should follow the required ones.

## Linking
- Use relative links to reference other docs within this tree.
- When information already exists elsewhere in `docs`, link to it instead of repeating the content.
- Keep anchors stable so other documents can link reliably.

## Naming conventions
- File and directory names should be lowercase with hyphens.
- Use `index.md` for directory landing pages where appropriate.

## Example frontmatter
```yaml
---
title: Example Document
description: A short introduction to the example.
tags: [example]
updated: 2025-06-21
---
```
