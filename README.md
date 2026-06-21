# Oriz Paper — Print tools

> Print-ready generators for everyday paper — lined sheets, dot grids, graph paper, planners, calendars, labels, and more, exported as crisp, press-ready PDFs straight from the browser.

**Live at**: <https://print.oriz.in> · **Status**: scaffold

## What this is

Paper turns parameters into print-ready PDFs. Pick a sheet style, tune it, and download — all generation happens locally in the browser, so layouts stay private and rendering is instant.

## Per-feature inventory

| Feature                     | Status     |
| --------------------------- | ---------- |
| (tools not yet implemented) | 📜 planned |

## App-specific env vars

None beyond the family-wide set at `templates/.env.example`.

## Local dev

```bash
# from the workspace root (c:/D/oriz)
pnpm -F oriz-paper-print-tools-app dev
```

## Knowledge

See [`./knowledge/`](./knowledge/) for app-specific decisions, runbooks, and services. Family rules / decisions / architecture live at the master repo's [`knowledge/`](../../../../knowledge/).

## License

MIT License. See master [`LICENSE`](../../../../LICENSE) — same terms across the family.
