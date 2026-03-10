# CLAUDE.md

This file provides guidance for AI agents working in this repository.

## What this repo is

A personal documentation repository for Benjamin Chait (he/him). It contains work philosophy, product management frameworks, reusable templates, and curated resources. There is no code, no build process, and no dependencies—everything here is Markdown.

## Repository structure

| File/Directory | Purpose |
|---|---|
| `README.md` | Brief intro; links to `how-to-benjamin.md` |
| `how-to-benjamin.md` | Core document: values, principles, frameworks, communication preferences |
| `glossary.md` | Terms and shorthand Benjamin uses |
| `retrospectives.md` | Guide for running team retrospectives |
| `product-management-resources.md` | Curated reading list, blogs, communities, and PM resources |
| `virtual-card.md` | Personal contact card |
| `templates/` | Reusable templates (SBAR, 1-pager, 1x1, PRD, retrospective) |

## Writing conventions

- **Voice**: First-person ("I"), direct, and plain. Avoid corporate jargon.
- **Tone**: Thoughtful and human. Matches the rest of the docs.
- **Format**: GitHub-flavored Markdown. Use headers, bullets, and tables where they aid clarity—not for decoration.
- **Length**: Concise. These docs are meant to be skimmed and referenced, not read linearly.
- **Links**: External links (Google Docs, articles, books) are common and intentional. Preserve them.

## Terminology

Refer to `glossary.md` for terms Benjamin uses (e.g., DRI, SBAR, MECE, rubber ducking, one-way vs two-way doors). Use this vocabulary consistently when editing or adding content.

## How to make changes

There is nothing to build, lint, or test. Changes are:

1. Edit the relevant `.md` file directly.
2. Commit with a clear message describing what changed and why (e.g., `Add RICE framework to how-to-benjamin.md`).
3. Push to the working branch.

Keep commits small and scoped to one file or topic when possible, consistent with the existing commit history.

## What agents should and shouldn't do

**Do:**
- Edit or extend existing documents when asked.
- Follow the voice and tone of the existing content.
- Use glossary terms where appropriate.
- Keep changes minimal and focused—don't refactor or reorganize without being asked.

**Don't:**
- Add code, scripts, tooling, or CI/CD configuration unless explicitly requested.
- Invent content (new frameworks, opinions, personal details) not grounded in what's already here.
- Change Benjamin's stated preferences, values, or voice.
- Rename or restructure files without explicit instruction.
