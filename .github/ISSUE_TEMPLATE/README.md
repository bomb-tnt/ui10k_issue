# Issue handling guide for ui10k

Thanks for helping improve **ui10k** — a deterministic dataset of 10,000 renderable
UI components across 74 real brand design systems, served over web, CLI, REST and MCP.

Live site: <https://ui10k.looptheworld.cloud/>

## Before opening an issue

1. **Search existing issues** — your problem may already be reported.
2. **Check the surfaces below** to decide which template fits best.
3. Try to include the exact **entry id** (it is part of the entry page URL, e.g.
   `/entry/accordion-binance-border-boxed-icon-none-spacing-comfortable-loading`).

## Which template should I use? / 该用哪个模板？

| Situation | Template |
|-----------|----------|
| Something is broken: page error, wrong filter results, API returns unexpected data, layout glitches | 🐛 **Bug Report** |
| A component entry itself looks wrong: unreadable contrast, bad markup, wrong brand tokens, mislabeled tags, duplicates | 🔍 **Data Quality Issue** |
| You want a new feature on the site/API, or a new family/style/state in the dataset | ✨ **Feature Request** |
| Question about usage, licensing, or anything else | 📄 **Blank Issue** |

## Useful references when writing your report

- Browse & filter entries: <https://ui10k.looptheworld.cloud/browse>
- Search API: `GET https://ui10k.looptheworld.cloud/api/v1/search?q=<term>`
- List all brand styles: <https://ui10k.looptheworld.cloud/api/v1/styles>
- Dataset manifest (counts, seeds, rejection reasons): <https://ui10k.looptheworld.cloud/api/v1/manifest>
- OpenAPI spec: <https://ui10k.looptheworld.cloud/api/v1/openapi.json>
- Entry JSON schema: `GET /api/v1/schema?kind=entry`
- Health check: <https://ui10k.looptheworld.cloud/api/v1/health>

## Tips for high-quality reports / 高质量报告的要点

- ✅ One issue per topic — don't mix a bug and a feature request.
- ✅ Use minimal reproduction steps; paste URLs rather than screenshots of URLs.
- ✅ For data issues, list affected entry ids one per line (a batch is fine).
- ✅ Include browser + OS for visual/layout bugs; include the full request/response for API bugs.
- ❌ Avoid "something is wrong on the site" without an entry id, URL, or screenshot.

## Labels we use / 标签说明

| Label | Meaning |
|-------|---------|
| `bug` | Confirmed or suspected defect |
| `data-quality` | Problem with a specific dataset entry |
| `enhancement` | New feature or improvement |
| `triage` | Newly opened, awaiting maintainer review |
| `good first issue` | Approachable for first-time contributors |
| `help wanted` | Maintainer specifically welcomes a PR |

## Language / 语言

Issues in **Chinese or English** are both welcome — write whatever you are most
comfortable with. Templates are bilingual to help you structure the report.

欢迎使用中文或英文提交 issue，模板为双语，按你习惯的语言填写即可。
