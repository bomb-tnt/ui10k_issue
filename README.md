# ui10k — Issue Tracker

Issue repository for **[ui10k](https://ui10k.looptheworld.cloud/)**: a deterministic
dataset of **10,000 renderable UI components** across **74 real brand design systems**
(Airbnb, Apple, BMW, Claude, Stripe…), served over web, CLI, REST and MCP.

> 本仓库是 ui10k 网站（<https://ui10k.looptheworld.cloud/>）的 Issue 反馈仓库。
> 网站、API 或数据集中的任何问题，欢迎在此提交 issue。

## 🐛 Report an issue / 提交问题

Go to [**New issue**](https://github.com/bomb-tnt/ui10k_issue/issues/new/choose) and pick a template:

| Template | Use it for / 适用于 |
|----------|----------------------|
| 🐛 **Bug Report** | Broken pages, wrong filter results, API errors 页面故障、筛选结果错误、API 异常 |
| 🔍 **Data Quality Issue** | Unreadable contrast, bad markup, wrong brand tokens, duplicates 对比度不可读、标记错误、token 不正确、重复条目 |
| ✨ **Feature Request** | New site/API features, new families/styles/states in the dataset 新功能或数据集新内容 |
| 📄 **Blank Issue** | Questions and anything else 其他问题 |

Issues in **Chinese or English** are both welcome. 中英文均可。

The full guide to writing high-quality reports (what info to include, labels we use)
lives in [`.github/ISSUE_TEMPLATE/README.md`](.github/ISSUE_TEMPLATE/README.md).

## 🔗 Useful links

- Live site: <https://ui10k.looptheworld.cloud/>
- Browse & filter: <https://ui10k.looptheworld.cloud/browse>
- REST API spec (OpenAPI): <https://ui10k.looptheworld.cloud/api/v1/openapi.json>
- Dataset manifest: <https://ui10k.looptheworld.cloud/api/v1/manifest>
- Health check: <https://ui10k.looptheworld.cloud/api/v1/health>

## 💡 Tip when reporting data problems

Include the exact **entry id** — it is part of the entry page URL, e.g.

```text
https://ui10k.looptheworld.cloud/entry/accordion-binance-border-boxed-icon-none-spacing-comfortable-loading
                                       └──────────────────────── entry id ────────────────────────┘
```

or find it via the search API: `GET /api/v1/search?q=<term>`.
