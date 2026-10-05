---
created_on: 2026-10-04 19:34
last_modified: 2026-10-04 19:34
status: current
---

# GitHub profile README

This documentation-only repository contains the README displayed on Alex Gorbatchev's GitHub profile.

## Verification

- Inspect pending changes: `git status --short` and `git diff -- README.md AGENTS.md`.
- Check whitespace: `git diff --check`.
- There is no application code, build system, or test suite here.

## README conventions

- Feature dotfiles first and devhost immediately after it, using descriptive paragraphs and documentation links.
- Sort project bullets alphabetically by repository name within each section.
- Keep AI tools and AI libraries in separate sections. Put `agent-parser`, `agent-watcher`, and `typescript-ai-policy` under AI libraries.
- Group domain-specific projects by subject: `djtools` belongs under Music and DJ tools.
- Keep descriptions concise, factual, and focused on what each project does. Avoid labels such as "My main project."
- Verify project names, public URLs, and descriptions against repository documentation or GitHub metadata before adding them.
- Identify direct ports and maintained forks, and link to their upstream projects.
- Preserve user edits and existing section order unless a requested change requires moving content.

## Boundaries

- Always read the applicable documentation skills before editing README.md or AGENTS.md.
- Always record new maintenance instructions in this file; ask before changing conflicting existing instructions.
- Keep temporary inspection files under `.tmp/` and remove files you created when finished.
- Never include credentials, token-bearing URLs, private hostnames, or machine-specific paths in the profile README.
- Never publish releases, tags, packages, or production deployments without explicit user authorization.
- Commit and push only when requested. Include only the authorized changes and leave unrelated work untouched.

## Profile behavior

The repository name must remain `alexgorbatchev`, its visibility must remain public, and the nonempty README.md must stay at the root for GitHub to display it on the profile.
