# 动手用AI

> Source: **跟李沐学AI** - Snapshot: **2026-10-11** - **17** episodes.
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

## All 17 episodes

| # | speaker | affiliation | topic | length | B station |
|---:|---|---|---|---:|---|
| 1 | - | - | 在讲 OpenAI Whisper 前先做了一个剪视频小工具【论文精读·44】 | 23:39 | [link](https://www.bilibili.com/video/BV1Pe4y1t7de) |
| 2 | - | - | AutoGluon背后的技术 | 3:48 | [link](https://www.bilibili.com/video/BV1F84y1F7Ps) |
| 3 | - | - | Windows 上安装和使用 AutoGluon v0.4 | 1:36 | [link](https://www.bilibili.com/video/BV1yL4y177hH) |
| 4 | - | - | 做了个实时数字人，水平吊打我自己 | 2:23 | [link](https://www.bilibili.com/video/BV1pB586fEap) |
| 5 | - | - | 适合新手的 100TB 数据存储方案【100亿模型计划】 | 40:42 | [link](https://www.bilibili.com/video/BV1Re4y1z7ce) |
| 6 | - | - | Windows 下安装 CUDA 和 Pytorch 跑深度学习 - 动手学深度学习v2 | 7:53 | [link](https://www.bilibili.com/video/BV18K411w7Vs) |
| 7 | - | - | 环境安装，BERT、GPT、T5 性能测试，和横向对比【100亿模型计划】 | 63:12 | [link](https://www.bilibili.com/video/BV1LT411F77M) |
| 8 | - | - | 能跟你对话的TTS【开源】 | 1:01 | [link](https://www.bilibili.com/video/BV1RfEw6LEfF) |
| 9 | - | - | 10行代码战胜90%数据科学家？ | 3:20 | [link](https://www.bilibili.com/video/BV1rh411m7Hb) |
| 10 | - | - | 古法做视频里加一点点科技 | 1:56 | [link](https://www.bilibili.com/video/BV1ScKR6QEQF) |
| 11 | - | - | 使用 AWS 最便宜的 GPU 实例 - 动手学深度学习v2 | 8:15 | [link](https://www.bilibili.com/video/BV1MA411L78X) |
| 12 | - | - | 安静、高性价比双卡装机【100亿模型计划】 | 36:53 | [link](https://www.bilibili.com/video/BV1NB4y1L7R8) |
| 13 | - | - | 高性价比的 500TB 数据存储方案【100亿模型计划】 | 42:54 | [link](https://www.bilibili.com/video/BV1ut4y1M7q5) |
| 14 | - | - | 肝了6个月的AudioLLM，开源了【100亿模型计划】 | 23:40 | [link](https://www.bilibili.com/video/BV1LGbozkEDY) |
| 15 | - | - | 给小朋友做的AI工具：把喜欢的书读出来 | 13:28 | [link](https://www.bilibili.com/video/BV1xbkkYGEQq) |
| 16 | - | - | 立个flag，续更【100亿模型计划】 | 0:43 | [link](https://www.bilibili.com/video/BV1aCgMzHELG) |
| 17 | - | - | 单卡、多卡 BERT、GPT2 训练性能【100亿模型计划】 | 50:23 | [link](https://www.bilibili.com/video/BV1fG411G7eH) |

## Per entry

- **在讲 OpenAI Whisper 前先做了一个剪视频小工具【论文精读·44】**
  - [B station](https://www.bilibili.com/video/BV1Pe4y1t7de)
  - links: https://github.com/mli/paper-reading
- **AutoGluon背后的技术**
  - [B station](https://www.bilibili.com/video/BV1F84y1F7Ps)
  - links: https://arxiv.org/abs/2003.06505 https://auto.gluon.ai/ https://github.com/awslabs/autogluon
- **Windows 上安装和使用 AutoGluon v0.4**
  - [B station](https://www.bilibili.com/video/BV1yL4y177hH)
- **做了个实时数字人，水平吊打我自己**
  - [B station](https://www.bilibili.com/video/BV1pB586fEap)
  - links: https://www.boson.ai/blog/higgs-avatar-v1 https://tally.so/r/VLvKgE
- **适合新手的 100TB 数据存储方案【100亿模型计划】**
  - [B station](https://www.bilibili.com/video/BV1Re4y1z7ce)
- **Windows 下安装 CUDA 和 Pytorch 跑深度学习 - 动手学深度学习v2**
  - [B station](https://www.bilibili.com/video/BV18K411w7Vs)
  - links: https://courses.d2l.ai/zh-v2/ https://zh-v2.d2l.ai/
- **环境安装，BERT、GPT、T5 性能测试，和横向对比【100亿模型计划】**
  - [B station](https://www.bilibili.com/video/BV1LT411F77M)
- **能跟你对话的TTS【开源】**
  - [B station](https://www.bilibili.com/video/BV1RfEw6LEfF)
  - links: https://www.boson.ai/workspace/avatar-preview https://www.boson.ai/blog/higgs-audio-v3-tts https://docs.boson.ai/models/higgs-audio-tts/overview
- **10行代码战胜90%数据科学家？**
  - [B station](https://www.bilibili.com/video/BV1rh411m7Hb)
  - links: https://www.kaggle.com/c/california-house-prices/overview https://auto.gluon.ai/ https://github.com/awslabs/autogluon
- **古法做视频里加一点点科技**
  - [B station](https://www.bilibili.com/video/BV1ScKR6QEQF)
- **使用 AWS 最便宜的 GPU 实例 - 动手学深度学习v2**
  - [B station](https://www.bilibili.com/video/BV1MA411L78X)
  - links: https://courses.d2l.ai/zh-v2/ https://zh-v2.d2l.ai/
- **安静、高性价比双卡装机【100亿模型计划】**
  - [B station](https://www.bilibili.com/video/BV1NB4y1L7R8)
- **高性价比的 500TB 数据存储方案【100亿模型计划】**
  - [B station](https://www.bilibili.com/video/BV1ut4y1M7q5)
- **肝了6个月的AudioLLM，开源了【100亿模型计划】**
  - [B station](https://www.bilibili.com/video/BV1LGbozkEDY)
- **给小朋友做的AI工具：把喜欢的书读出来**
  - [B station](https://www.bilibili.com/video/BV1xbkkYGEQq)
  - links: https://readtogether.ai/ https://readtogether.canny.io/discussion
- **立个flag，续更【100亿模型计划】**
  - [B station](https://www.bilibili.com/video/BV1aCgMzHELG)
- **单卡、多卡 BERT、GPT2 训练性能【100亿模型计划】**
  - [B station](https://www.bilibili.com/video/BV1fG411G7eH)