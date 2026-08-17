# Project: frida-bio

A single-page link-in-bio site for Frida ("learning Claude and exploring what AI can build").

## Structure
- `index.html` — the entire site (HTML/CSS inline, no build step, no dependencies).
- `.claude/launch.json` — local preview config; serves the page at `http://localhost:8090` via `python3 -m http.server 8090`.

## Conventions
- Keep it a static, dependency-free single file unless there's a real reason to split it up.
- Preview changes with the `frida-bio` launch config before calling a visual change done.

## Notes
- This is a learning project — favor clear, simple code over clever abstractions.

<!--
Subfolder CLAUDE.md files: if this project grows separate areas (e.g. /blog, /admin),
add a CLAUDE.md inside that subfolder for context specific to working in that area.
Claude Code loads it automatically when the session's working context is inside that folder.
-->
