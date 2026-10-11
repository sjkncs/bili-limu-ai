# 跟李沐学AI · 视频索引（B 站）

> Snapshot: **2026-10-11** - **106** episodes, one directory per content type.

- **跟李沐学AI**

## Contents

| directory | type | source | episodes | full title | arXiv | speaker |
|---|---|---|---:|---:|---:|---:|
| [`01-paper-reading/`](01-paper-reading/) | AI 论文精读 | 跟李沐学AI | 60 | 0 | 0 | 0 |
| [`02-hands-on-ai/`](02-hands-on-ai/) | 动手用AI | 跟李沐学AI | 17 | 0 | 1 | 0 |
| [`03-ml-course/`](03-ml-course/) | 斯坦福实用机器学习 | 跟李沐学AI | 29 | 0 | 0 | 0 |
| | | **total** | **106** | | | |

## Data source / method / limits

**Data source**: `seasons_archives_list` for episode lists; `x/web-interface/view`
per video for the **`desc`** field. Every request goes through a backoff wrapper because
the anonymous API answers risk-control code `-352` under load.

**Method**: directory assignment uses an **explicit map of exact collection names** -- a
fuzzy match silently dropped one whole conference series once (48 instead of 96 items).
Parsing then depends on the source's description shape (paper template / guest-intro block /
title-only).

**Limits**
- Metadata index only: no videos, no subtitles, no slides.
- Bilibili caps video **titles** at 80 chars. Where a source writes full paper names in the
  description, `full_title` is complete while `bvid_title` may be truncated.
- Sources without a description template expose fewer fields; those stay empty and are
  **not guessed**.
- Data was collected with backoff and is a snapshot, not a live view.

---
*2026-10-11 snapshot. All content belongs to the original authors.*