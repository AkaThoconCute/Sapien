# ADR (Architecture Decision Records)

## 1. Introduction

ADR records the architecture decisions of Sapien: what was decided, why, and the trade-offs.

**Sapien** is a knowledge management ecosystem: write articles, publish them to GitHub as Markdown, search them, check their quality, and render them as web pages. It has these sub-projects:

- **Atelier**: article authoring (create, edit, metadata, templates, review, version).
- **Atlas**: publish Markdown files to GitHub, retry on failure, deprecate and archive articles.
- **Falcon**: fast search over content pulled from GitHub, plus the Structured Center Data Pool.
- **Merlin**: content improvement and inspection (SEO, images, ...), plus AI agents: ARR (suggests updates to related articles when a source document changes) and PCP (chat with AI to draft or edit articles, custom rules, MCP from VS Code).
- **Prism**: render Markdown on GitHub into Live pages when a PR is created or merged.

2.
