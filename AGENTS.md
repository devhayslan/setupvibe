# Repository Guidelines

## Project Structure & Module Organization

`desktop.sh` and `server.sh` are the main entry points. `desktop.sh` targets macOS and Linux developer machines; `server.sh` targets Linux servers. Shared configuration templates live in `conf/` (`tmux.conf`, `zshrc-*.zsh`, `ecosystem.config.js`). User-facing documentation is under `docs/desktop/en/`, `docs/desktop/pt-br/`, `docs/desktop/fr/`, and `docs/desktop/es/`. Keep changes localized: installer logic in the shell scripts, deployable templates in `conf/`, and explanatory material in `docs/`.

## Build, Test, and Development Commands

There is no build system or package manifest in this repository. Use direct execution and syntax checks:

```bash
bash desktop.sh
bash server.sh
bash -n desktop.sh
bash -n server.sh
node -c conf/ecosystem.config.js
```

Run the target script locally for development. Use `bash -n` before committing to catch shell syntax errors. Validate `conf/ecosystem.config.js` with Node after editing PM2 settings. For release-style verification, test on a clean VM or machine matching the supported platforms.

## Coding Style & Naming Conventions

Shell is Bash-first. Follow the existing style: 4-space indentation inside functions, uppercase environment/constants (`VERSION`, `REAL_HOME`), and helper functions in lowercase (`user_do`, `sys_do`, `safe_download`). Keep step functions sequential and descriptive (`step_1`, `step_2`, ...). Prefer small helper functions over duplicated install logic. Preserve comments that explain platform-specific behavior, privilege handling, or package-repository workarounds.

## Testing Guidelines

Automated tests are not present, so contributors should rely on syntax validation plus manual smoke tests. At minimum, run `bash -n` on edited scripts. If behavior changes, execute the affected installer on the intended OS family and confirm the relevant config files land in the expected home-directory paths. Update docs when installation steps, supported platforms, or installed toolsets change.

## Commit & Pull Request Guidelines

Recent history favors short, prefix-based commit subjects such as `docs: ...`, `fixes: ...`, and occasional `Refactor ...`. Keep commits imperative and scoped to one concern. PRs should include a brief summary, affected platforms (`macOS`, `Ubuntu`, `Debian`, `Zorin`), manual verification performed, and screenshots only when documentation output or terminal UX materially changed.

## Security & Configuration Notes

Do not hardcode secrets, tokens, or machine-specific paths. Changes affecting privilege elevation, APT keyrings, downloaded remote scripts, or files written to `$HOME` should be reviewed carefully and called out explicitly in the PR description.

## Markdown Standards

All `.md` files in this project must follow these rules:

1. **Headings** — use hierarchical `#` (H1 → H2 → H3), never skip levels.
2. **Tables** — columns aligned with pipes `|`, always include a separator row `|---|---|`.
3. **Code blocks** — always specify the language (` ```bash `, ` ```js `, etc.).
4. **Links** — use `[text](url)` format, never bare URLs.
5. **Lists** — hyphens `-` for unordered items; numbers for ordered lists.
6. **Blank lines** — one blank line before and after headings, code blocks, and tables.
7. **No inline HTML** — do not use `<br>`, `<b>`, `<i>` or other tags inside Markdown.
8. **Footer link** — every `.md` file must end with a formatting reference footer:

```markdown
---
> Follow the formatting guide: [Markdown Format Guide](.claude/commands/markdown-format.md)
```

---
> Follow the formatting guide: [Markdown Format Guide](.claude/commands/markdown-format.md)
