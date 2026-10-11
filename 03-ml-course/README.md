# 斯坦福实用机器学习

> Source: **跟李沐学AI** - Snapshot: **2026-10-11** - **29** episodes.
> Data: [`items.json`](items.json)

## Data source / method / limits

**Data source**: `seasons_archives_list` for the episode list; `x/web-interface/view`
per video for its **`desc`** field.

**Method**: this source's titles are already short and complete (no 80-char truncation
observed), so **the title is the record** and no paper/venue/speaker parsing is attempted.
The description is scanned only for links, and links are de-duplicated per episode.

**Limits**: descriptions are shallow and highly repetitive -- the most frequent link
appears on 42 of 106 episodes (an authoritative paper-list repo), another on 29 (a course
homepage) -- so links points at entry points rather than at each individual paper.
**No venue, arXiv id or speaker is available for most entries, and none is invented.**
16 of 106 descriptions are empty entirely.

## All 29 episodes

| # | speaker | affiliation | topic | length | B station |
|---:|---|---|---|---:|---|
| 1 | - | - | 9.2 超参数优化【斯坦福21秋季：实用机器学习中文版】 | 40:41 | [link](https://www.bilibili.com/video/BV1FM4y1c7yG) |
| 2 | - | - | 3.7 循环神经网络【斯坦福21秋季：实用机器学习中文版】 | 20:57 | [link](https://www.bilibili.com/video/BV1pq4y1r7zo) |
| 3 | - | - | 5.3 Boosting【斯坦福21秋季：实用机器学习中文版】 | 14:42 | [link](https://www.bilibili.com/video/BV1aM4y1P7z9) |
| 4 | - | - | 2.4 特征工程【斯坦福21秋季：实用机器学习中文版】 | 19:59 | [link](https://www.bilibili.com/video/BV1t44y1x7Hw) |
| 5 | - | - | 5.4 Stacking【斯坦福21秋季：实用机器学习中文版】 | 22:03 | [link](https://www.bilibili.com/video/BV1PZ4y197CX) |
| 6 | - | - | 11.1 迁移学习【斯坦福21秋季：实用机器学习中文版】 | 29:58 | [link](https://www.bilibili.com/video/BV1SL4y1t7ZL) |
| 7 | - | - | 4.2 过拟合和欠拟合【斯坦福21秋季：实用机器学习中文版】 | 29:37 | [link](https://www.bilibili.com/video/BV1ah411t7Pp) |
| 8 | - | - | 2.3 数据变换【斯坦福21秋季：实用机器学习中文版】 | 27:48 | [link](https://www.bilibili.com/video/BV1pQ4y167ej) |
| 9 | - | - | 4.1 模型评估【斯坦福21秋季：实用机器学习中文版】 | 35:07 | [link](https://www.bilibili.com/video/BV1tQ4y1S7Ty) |
| 10 | - | - | 1.4 数据标注【斯坦福21秋季：实用机器学习中文版】 | 37:32 | [link](https://www.bilibili.com/video/BV1HL41147aL) |
| 11 | - | - | 10.1 深度神经网络架构【斯坦福21秋季：实用机器学习中文版】 | 29:43 | [link](https://www.bilibili.com/video/BV1WY411p7Zp) |
| 12 | - | - | 3.4 随机梯度下降【斯坦福21秋季：实用机器学习中文版】 | 12:13 | [link](https://www.bilibili.com/video/BV1234y1m75j) |
| 13 | - | - | 9.1 模型调参【斯坦福21秋季：实用机器学习中文版】 | 20:29 | [link](https://www.bilibili.com/video/BV1vQ4y1e7LF) |
| 14 | - | - | 2.1 探索性数据分析【斯坦福21秋季：实用机器学习中文版】 | 34:51 | [link](https://www.bilibili.com/video/BV1Xh411p7M9) |
| 15 | - | - | 3.2 最简单也最常用的决策树【斯坦福21秋季：实用机器学习中文版】 | 15:57 | [link](https://www.bilibili.com/video/BV17u411f7dt) |
| 16 | - | - | 1.1 课程介绍【斯坦福21秋季：实用机器学习中文版】 | 38:58 | [link](https://www.bilibili.com/video/BV13U4y1N7Uo) |
| 17 | - | - | 3.6 卷积神经网络【斯坦福21秋季：实用机器学习中文版】 | 17:55 | [link](https://www.bilibili.com/video/BV1m34y1m7TD) |
| 18 | - | - | 4.3 模型验证【斯坦福21秋季：实用机器学习中文版】 | 23:07 | [link](https://www.bilibili.com/video/BV1Dh411x7hZ) |
| 19 | - | - | 1.3 网页数据抓取【斯坦福21秋季：实用机器学习中文版】 | 26:18 | [link](https://www.bilibili.com/video/BV1JM4y137kK) |
| 20 | - | - | 1.2 数据获取【斯坦福21秋季：实用机器学习中文版】 | 30:50 | [link](https://www.bilibili.com/video/BV1Lf4y1n7LN) |
| 21 | - | - | 5.1 方差和偏差【斯坦福21秋季：实用机器学习中文版】 | 17:00 | [link](https://www.bilibili.com/video/BV1H44y1v7Kf) |
| 22 | - | - | 2.5 数据科学家的日常【斯坦福21秋季：实用机器学习中文版】 | 9:32 | [link](https://www.bilibili.com/video/BV1KL411G7BX) |
| 23 | - | - | 9.3 网络架构搜索【斯坦福21秋季：实用机器学习中文版】 | 24:02 | [link](https://www.bilibili.com/video/BV1gP4y1H7Rd) |
| 24 | - | - | 3.5 多层感知机【斯坦福21秋季：实用机器学习中文版】 | 11:44 | [link](https://www.bilibili.com/video/BV1ST4y1R7uC) |
| 25 | - | - | 5.2 Bagging【斯坦福21秋季：实用机器学习中文版】 | 16:50 | [link](https://www.bilibili.com/video/BV13g411N7xy) |
| 26 | - | - | 3.1 8分钟机器学习介绍【斯坦福21秋季：实用机器学习中文版】 | 8:43 | [link](https://www.bilibili.com/video/BV1Nv411u7bW) |
| 27 | - | - | 11.2 NLP中的微调【斯坦福21秋季：实用机器学习中文版】 | 21:25 | [link](https://www.bilibili.com/video/BV1bq4y1y7tg) |
| 28 | - | - | 2.2 数据清理【斯坦福21秋季：实用机器学习中文版】 | 18:53 | [link](https://www.bilibili.com/video/BV1kQ4y1Q7mx) |
| 29 | - | - | 3.3 最简单也同样最常用的线性模型【斯坦福21秋季：实用机器学习中文版】 | 14:50 | [link](https://www.bilibili.com/video/BV1eh411b7ZW) |

## Per entry

- **9.2 超参数优化【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1FM4y1c7yG)
  - links: https://c.d2l.ai/stanford-cs329p/
- **3.7 循环神经网络【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1pq4y1r7zo)
  - links: https://c.d2l.ai/stanford-cs329p/
- **5.3 Boosting【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1aM4y1P7z9)
  - links: https://c.d2l.ai/stanford-cs329p/
- **2.4 特征工程【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1t44y1x7Hw)
  - links: https://c.d2l.ai/stanford-cs329p/
- **5.4 Stacking【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1PZ4y197CX)
  - links: https://c.d2l.ai/stanford-cs329p/
- **11.1 迁移学习【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1SL4y1t7ZL)
  - links: https://c.d2l.ai/stanford-cs329p/
- **4.2 过拟合和欠拟合【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1ah411t7Pp)
  - links: https://c.d2l.ai/stanford-cs329p/
- **2.3 数据变换【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1pQ4y167ej)
  - links: https://c.d2l.ai/stanford-cs329p/
- **4.1 模型评估【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1tQ4y1S7Ty)
  - links: https://c.d2l.ai/stanford-cs329p/
- **1.4 数据标注【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1HL41147aL)
  - links: https://c.d2l.ai/stanford-cs329p/
- **10.1 深度神经网络架构【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1WY411p7Zp)
  - links: https://c.d2l.ai/stanford-cs329p/
- **3.4 随机梯度下降【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1234y1m75j)
  - links: https://c.d2l.ai/stanford-cs329p/
- **9.1 模型调参【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1vQ4y1e7LF)
  - links: https://c.d2l.ai/stanford-cs329p/
- **2.1 探索性数据分析【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1Xh411p7M9)
  - links: https://c.d2l.ai/stanford-cs329p/
- **3.2 最简单也最常用的决策树【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV17u411f7dt)
  - links: https://c.d2l.ai/stanford-cs329p/
- **1.1 课程介绍【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV13U4y1N7Uo)
  - links: https://c.d2l.ai/stanford-cs329p/
- **3.6 卷积神经网络【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1m34y1m7TD)
  - links: https://c.d2l.ai/stanford-cs329p/
- **4.3 模型验证【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1Dh411x7hZ)
  - links: https://c.d2l.ai/stanford-cs329p/
- **1.3 网页数据抓取【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1JM4y137kK)
  - links: https://c.d2l.ai/stanford-cs329p/
- **1.2 数据获取【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1Lf4y1n7LN)
  - links: https://c.d2l.ai/stanford-cs329p/
- **5.1 方差和偏差【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1H44y1v7Kf)
  - links: https://c.d2l.ai/stanford-cs329p/
- **2.5 数据科学家的日常【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1KL411G7BX)
  - links: https://c.d2l.ai/stanford-cs329p/
- **9.3 网络架构搜索【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1gP4y1H7Rd)
  - links: https://c.d2l.ai/stanford-cs329p/
- **3.5 多层感知机【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1ST4y1R7uC)
  - links: https://c.d2l.ai/stanford-cs329p/
- **5.2 Bagging【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV13g411N7xy)
  - links: https://c.d2l.ai/stanford-cs329p/
- **3.1 8分钟机器学习介绍【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1Nv411u7bW)
  - links: https://c.d2l.ai/stanford-cs329p/
- **11.2 NLP中的微调【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1bq4y1y7tg)
  - links: https://c.d2l.ai/stanford-cs329p/
- **2.2 数据清理【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1kQ4y1Q7mx)
  - links: https://c.d2l.ai/stanford-cs329p/
- **3.3 最简单也同样最常用的线性模型【斯坦福21秋季：实用机器学习中文版】**
  - [B station](https://www.bilibili.com/video/BV1eh411b7ZW)
  - links: https://c.d2l.ai/stanford-cs329p/