# AI 论文精读

> Source: **跟李沐学AI** - Snapshot: **2026-10-11** - **60** episodes.
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

## All 60 episodes

| # | speaker | affiliation | topic | length | B station |
|---:|---|---|---|---:|---|
| 1 | - | - | AlexNet论文逐段精读【论文精读】 | 55:21 | [link](https://www.bilibili.com/video/BV1hq4y157t1) |
| 2 | - | - | GPipe论文精读【论文精读】 | 58:48 | [link](https://www.bilibili.com/video/BV1v34y1E7zu) |
| 3 | - | - | OpenAI Codex 论文精读【论文精读】 | 47:59 | [link](https://www.bilibili.com/video/BV1iY41137Zi) |
| 4 | - | - | ResNet论文逐段精读【论文精读】 | 53:46 | [link](https://www.bilibili.com/video/BV1P3411y7nn) |
| 5 | - | - | 斯坦福 2022 年 AI 指数报告精读【论文精读】 | 79:56 | [link](https://www.bilibili.com/video/BV1s44y1N7eu) |
| 6 | - | - | 多模态论文串讲·上【论文精读·46】 | 72:25 | [link](https://www.bilibili.com/video/BV1Vd4y1v77v) |
| 7 | - | - | 如何找研究想法 1【论文精读】 | 5:35 | [link](https://www.bilibili.com/video/BV1qq4y1z7F2) |
| 8 | - | - | Neural Corpus Indexer 文档检索【论文精读·47】 | 55:47 | [link](https://www.bilibili.com/video/BV1Se411w7Sn) |
| 9 | - | - | Megatron LM 论文精读【论文精读】 | 56:08 | [link](https://www.bilibili.com/video/BV1nB4y1R7Yz) |
| 10 | - | - | 理由、论据和担保【研究的艺术·四】 | 44:14 | [link](https://www.bilibili.com/video/BV1SB4y1a75c) |
| 11 | - | - | 如何读论文【论文精读·1】 | 6:39 | [link](https://www.bilibili.com/video/BV1H44y1t75x) |
| 12 | - | - | 视频理解论文串讲（上）【论文精读】 | 51:15 | [link](https://www.bilibili.com/video/BV1fL4y157yA) |
| 13 | - | - | ViT论文逐段精读【论文精读】 | 71:31 | [link](https://www.bilibili.com/video/BV15P4y137jb) |
| 14 | - | - | Llama 3.1论文精读 · 4. 训练infra【论文精读·54】 | 25:05 | [link](https://www.bilibili.com/video/BV1b4421f7fa) |
| 15 | - | - | 双流网络论文逐段精读【论文精读】 | 52:57 | [link](https://www.bilibili.com/video/BV1mq4y1x7RU) |
| 16 | - | - | OpenAI Whisper 精读【论文精读·45】 | 72:16 | [link](https://www.bilibili.com/video/BV1VG4y1t74x) |
| 17 | - | - | DeepMind AlphaCode 论文精读【论文精读】 | 44:01 | [link](https://www.bilibili.com/video/BV1ab4y1s7rc) |
| 18 | - | - | GAN论文逐段精读【论文精读】 | 46:18 | [link](https://www.bilibili.com/video/BV1rb4y187vD) |
| 19 | - | - | 零基础多图详解图神经网络（GNN/GCN）【论文精读】 | 66:19 | [link](https://www.bilibili.com/video/BV1iT4y1d7zP) |
| 20 | - | - | MAE 论文逐段精读【论文精读】 | 47:04 | [link](https://www.bilibili.com/video/BV1sq4y1q77t) |
| 21 | - | - | 你（被）吐槽过论文不够 novel 吗？【论文精读】 | 14:11 | [link](https://www.bilibili.com/video/BV1ea41127Bq) |
| 22 | - | - | I3D 论文精读【论文精读】 | 52:31 | [link](https://www.bilibili.com/video/BV1tY4y1p7hq) |
| 23 | - | - | BERT 论文逐段精读【论文精读】 | 45:49 | [link](https://www.bilibili.com/video/BV1PL411M7eQ) |
| 24 | - | - | DETR 论文精读【论文精读】 | 54:23 | [link](https://www.bilibili.com/video/BV1GB4y1X72R) |
| 25 | - | - | CLIP 改进工作串讲（下）【论文精读·42】 | 64:26 | [link](https://www.bilibili.com/video/BV1gg411U7n4) |
| 26 | - | - | 讲好故事、论点【研究的艺术·三】 | 43:57 | [link](https://www.bilibili.com/video/BV1WB4y1v7ST) |
| 27 | - | - | AlphaFold 2 论文精读【论文精读】 | 75:29 | [link](https://www.bilibili.com/video/BV1oR4y1K7Xr) |
| 28 | - | - | Zero 论文精读【论文精读】 | 52:21 | [link](https://www.bilibili.com/video/BV1tY411g7ZT) |
| 29 | - | - | AlphaFold2论文精读预告【论文精读】 | 3:28 | [link](https://www.bilibili.com/video/BV1Eu411U7Te) |
| 30 | - | - | CLIP 改进工作串讲（上）【论文精读·42】 | 75:43 | [link](https://www.bilibili.com/video/BV1FV4y1p7Lm) |
| 31 | - | - | Pathways 论文精读【论文精读】 | 62:14 | [link](https://www.bilibili.com/video/BV1xB4y1m7Xi) |
| 32 | - | - | 9年后重读深度学习奠基作之一：AlexNet【论文精读·2】 | 18:59 | [link](https://www.bilibili.com/video/BV1ih411J7Kz) |
| 33 | - | - | Chain of Thought论文、代码和资源【论文精读·43】 | 33:23 | [link](https://www.bilibili.com/video/BV1t8411e7Ug) |
| 34 | - | - | Anthropic LLM 论文精读【论文精读·51】 | 61:52 | [link](https://www.bilibili.com/video/BV1XY411B7nM) |
| 35 | - | - | GPT，GPT-2，GPT-3 论文精读【论文精读】 | 89:59 | [link](https://www.bilibili.com/video/BV1AF411b7xQ) |
| 36 | - | - | 如何判断（你自己的）研究工作的价值【论文精读】 | 9:00 | [link](https://www.bilibili.com/video/BV1oL411c7Us) |
| 37 | - | - | Llama 3.1论文精读 · 1. 导言【论文精读·54】 | 18:53 | [link](https://www.bilibili.com/video/BV1WM4m1y7Uh) |
| 38 | - | - | 跟读者建立联系【研究的艺术·一】 | 45:02 | [link](https://www.bilibili.com/video/BV1hY411T7vy) |
| 39 | - | - | CLIP 论文逐段精读【论文精读】 | 98:26 | [link](https://www.bilibili.com/video/BV1SL4y1s7LQ) |
| 40 | - | - | 视频理解论文串讲（下）【论文精读】 | 68:32 | [link](https://www.bilibili.com/video/BV11Y411P7ep) |
| 41 | - | - | 撑起计算机视觉半边天的ResNet【论文精读】 | 11:50 | [link](https://www.bilibili.com/video/BV1Fb4y1h73E) |
| 42 | - | - | InstructGPT 论文精读【论文精读·48】 | 67:11 | [link](https://www.bilibili.com/video/BV1hd4y187CR) |
| 43 | - | - | 视频生成·上【论文精读·55】 | 64:18 | [link](https://www.bilibili.com/video/BV1VdcxesEAt) |
| 44 | - | - | DALL·E 2（内含扩散模型介绍）【论文精读】 | 87:55 | [link](https://www.bilibili.com/video/BV17r4y1u77B) |
| 45 | - | - | 参数服务器（Parameter Server）逐段精读【论文精读】 | 97:40 | [link](https://www.bilibili.com/video/BV1YA4y197G8) |
| 46 | - | - | MoCo 论文逐段精读【论文精读】 | 84:11 | [link](https://www.bilibili.com/video/BV1C3411s7t9) |
| 47 | - | - | Llama 3.1论文精读 · 3. 模型【论文精读·54】 | 26:16 | [link](https://www.bilibili.com/video/BV1Q4421Z7Tj) |
| 48 | - | - | Llama 3.1论文精读 · 5. 模型训练过程【论文精读·54】 | 10:42 | [link](https://www.bilibili.com/video/BV1c8HbeaEXi) |
| 49 | - | - | 明白问题的重要性【研究的艺术·二】 | 63:40 | [link](https://www.bilibili.com/video/BV11S4y1v7S2) |
| 50 | - | - | Transformer论文逐段精读【论文精读】 | 87:05 | [link](https://www.bilibili.com/video/BV1pu411o7BE) |
| 51 | - | - | 对比学习论文综述【论文精读】 | 92:01 | [link](https://www.bilibili.com/video/BV19S4y1M7hm) |
| 52 | - | - | ViLT 论文精读【论文精读】 | 63:26 | [link](https://www.bilibili.com/video/BV14r4y1j74y) |
| 53 | - | - | Llama 3.1论文精读 · 2. 预训练数据【论文精读·54】 | 23:37 | [link](https://www.bilibili.com/video/BV1u142187S5) |
| 54 | - | - | GPT-4论文精读【论文精读·53】 | 80:39 | [link](https://www.bilibili.com/video/BV1vM4y1U7b5) |
| 55 | - | - | 视频生成·下：模型和训练【论文精读·55】 | 62:50 | [link](https://www.bilibili.com/video/BV1U65SzuE4p) |
| 56 | - | - | Swin Transformer论文精读【论文精读】 | 60:22 | [link](https://www.bilibili.com/video/BV13L4y1475U) |
| 57 | - | - | HELM 全面语言模型评测【论文精读·50】 | 83:38 | [link](https://www.bilibili.com/video/BV1z24y1B7uX) |
| 58 | - | - | 大模型时代下做科研的四个思路【论文精读·52】 | 66:29 | [link](https://www.bilibili.com/video/BV1oX4y1d7X6) |
| 59 | - | - | Deepmind用机器学习指导数学直觉论文逐段精读【论文精读】 | 52:51 | [link](https://www.bilibili.com/video/BV1YZ4y1S72j) |
| 60 | - | - | 多模态论文串讲·下【论文精读·49】 | 63:29 | [link](https://www.bilibili.com/video/BV1fA411Z772) |

## Per entry

- **AlexNet论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1hq4y157t1)
- **GPipe论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1v34y1E7zu)
  - links: https://github.com/mli/paper-reading/
- **OpenAI Codex 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1iY41137Zi)
  - links: https://github.com/mli/paper-reading
- **ResNet论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1P3411y7nn)
- **斯坦福 2022 年 AI 指数报告精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1s44y1N7eu)
  - links: https://github.com/mli/paper-reading
- **多模态论文串讲·上【论文精读·46】**
  - [B station](https://www.bilibili.com/video/BV1Vd4y1v77v)
  - links: https://github.com/mli/paper-reading
- **如何找研究想法 1【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1qq4y1z7F2)
  - links: https://github.com/mli/paper-reading
- **Neural Corpus Indexer 文档检索【论文精读·47】**
  - [B station](https://www.bilibili.com/video/BV1Se411w7Sn)
  - links: https://github.com/mli/paper-reading
- **Megatron LM 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1nB4y1R7Yz)
  - links: https://github.com/mli/paper-reading/
- **理由、论据和担保【研究的艺术·四】**
  - [B station](https://www.bilibili.com/video/BV1SB4y1a75c)
  - links: https://github.com/mli/paper-reading
- **如何读论文【论文精读·1】**
  - [B station](https://www.bilibili.com/video/BV1H44y1t75x)
- **视频理解论文串讲（上）【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1fL4y157yA)
  - links: https://github.com/mli/paper-reading/
- **ViT论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV15P4y137jb)
  - links: https://github.com/mli/paper-reading
- **Llama 3.1论文精读 · 4. 训练infra【论文精读·54】**
  - [B station](https://www.bilibili.com/video/BV1b4421f7fa)
  - links: https://github.com/mli/paper-reading
- **双流网络论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1mq4y1x7RU)
  - links: https://github.com/mli/paper-reading
- **OpenAI Whisper 精读【论文精读·45】**
  - [B station](https://www.bilibili.com/video/BV1VG4y1t74x)
  - links: https://github.com/mli/paper-reading
- **DeepMind AlphaCode 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1ab4y1s7rc)
  - links: https://github.com/mli/paper-reading
- **GAN论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1rb4y187vD)
  - links: https://github.com/mli/paper-reading
- **零基础多图详解图神经网络（GNN/GCN）【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1iT4y1d7zP)
  - links: https://github.com/mli/paper-reading
- **MAE 论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1sq4y1q77t)
- **你（被）吐槽过论文不够 novel 吗？【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1ea41127Bq)
  - links: https://github.com/mli/paper-reading/
- **I3D 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1tY4y1p7hq)
  - links: https://github.com/mli/paper-reading
- **BERT 论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1PL411M7eQ)
  - links: https://github.com/mli/paper-reading
- **DETR 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1GB4y1X72R)
  - links: https://github.com/mli/paper-reading/
- **CLIP 改进工作串讲（下）【论文精读·42】**
  - [B station](https://www.bilibili.com/video/BV1gg411U7n4)
  - links: https://github.com/mli/paper-reading
- **讲好故事、论点【研究的艺术·三】**
  - [B station](https://www.bilibili.com/video/BV1WB4y1v7ST)
  - links: https://github.com/mli/paper-reading
- **AlphaFold 2 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1oR4y1K7Xr)
  - links: https://github.com/mli/paper-reading
- **Zero 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1tY411g7ZT)
  - links: https://github.com/mli/paper-reading/
- **AlphaFold2论文精读预告【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1Eu411U7Te)
- **CLIP 改进工作串讲（上）【论文精读·42】**
  - [B station](https://www.bilibili.com/video/BV1FV4y1p7Lm)
  - links: https://github.com/mli/paper-reading
- **Pathways 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1xB4y1m7Xi)
  - links: https://github.com/mli/paper-reading
- **9年后重读深度学习奠基作之一：AlexNet【论文精读·2】**
  - [B station](https://www.bilibili.com/video/BV1ih411J7Kz)
- **Chain of Thought论文、代码和资源【论文精读·43】**
  - [B station](https://www.bilibili.com/video/BV1t8411e7Ug)
  - links: https://github.com/mli/paper-reading
- **Anthropic LLM 论文精读【论文精读·51】**
  - [B station](https://www.bilibili.com/video/BV1XY411B7nM)
  - links: https://github.com/mli/paper-reading
- **GPT，GPT-2，GPT-3 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1AF411b7xQ)
  - links: https://github.com/mli/paper-reading
- **如何判断（你自己的）研究工作的价值【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1oL411c7Us)
- **Llama 3.1论文精读 · 1. 导言【论文精读·54】**
  - [B station](https://www.bilibili.com/video/BV1WM4m1y7Uh)
  - links: https://github.com/mli/paper-reading
- **跟读者建立联系【研究的艺术·一】**
  - [B station](https://www.bilibili.com/video/BV1hY411T7vy)
  - links: https://github.com/mli/paper-reading/
- **CLIP 论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1SL4y1s7LQ)
  - links: https://github.com/mli/paper-reading/
- **视频理解论文串讲（下）【论文精读】**
  - [B station](https://www.bilibili.com/video/BV11Y411P7ep)
  - links: https://github.com/mli/paper-reading/
- **撑起计算机视觉半边天的ResNet【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1Fb4y1h73E)
- **InstructGPT 论文精读【论文精读·48】**
  - [B station](https://www.bilibili.com/video/BV1hd4y187CR)
  - links: https://github.com/mli/paper-reading
- **视频生成·上【论文精读·55】**
  - [B station](https://www.bilibili.com/video/BV1VdcxesEAt)
  - links: https://github.com/mli/paper-reading
- **DALL·E 2（内含扩散模型介绍）【论文精读】**
  - [B station](https://www.bilibili.com/video/BV17r4y1u77B)
  - links: https://github.com/mli/paper-reading
- **参数服务器（Parameter Server）逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1YA4y197G8)
  - links: https://github.com/mli/paper-reading/
- **MoCo 论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1C3411s7t9)
  - links: https://github.com/mli/paper-reading
- **Llama 3.1论文精读 · 3. 模型【论文精读·54】**
  - [B station](https://www.bilibili.com/video/BV1Q4421Z7Tj)
  - links: https://github.com/mli/paper-reading
- **Llama 3.1论文精读 · 5. 模型训练过程【论文精读·54】**
  - [B station](https://www.bilibili.com/video/BV1c8HbeaEXi)
  - links: https://github.com/mli/paper-reading
- **明白问题的重要性【研究的艺术·二】**
  - [B station](https://www.bilibili.com/video/BV11S4y1v7S2)
  - links: https://github.com/mli/paper-reading
- **Transformer论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1pu411o7BE)
  - links: https://github.com/mli/paper-reading
- **对比学习论文综述【论文精读】**
  - [B station](https://www.bilibili.com/video/BV19S4y1M7hm)
  - links: https://github.com/mli/paper-reading/
- **ViLT 论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV14r4y1j74y)
  - links: https://github.com/mli/paper-reading
- **Llama 3.1论文精读 · 2. 预训练数据【论文精读·54】**
  - [B station](https://www.bilibili.com/video/BV1u142187S5)
  - links: https://github.com/mli/paper-reading
- **GPT-4论文精读【论文精读·53】**
  - [B station](https://www.bilibili.com/video/BV1vM4y1U7b5)
  - links: https://github.com/mli/paper-reading
- **视频生成·下：模型和训练【论文精读·55】**
  - [B station](https://www.bilibili.com/video/BV1U65SzuE4p)
  - links: https://github.com/mli/paper-reading
- **Swin Transformer论文精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV13L4y1475U)
  - links: https://github.com/mli/paper-reading
- **HELM 全面语言模型评测【论文精读·50】**
  - [B station](https://www.bilibili.com/video/BV1z24y1B7uX)
  - links: https://github.com/mli/paper-reading
- **大模型时代下做科研的四个思路【论文精读·52】**
  - [B station](https://www.bilibili.com/video/BV1oX4y1d7X6)
  - links: https://github.com/mli/paper-reading
- **Deepmind用机器学习指导数学直觉论文逐段精读【论文精读】**
  - [B station](https://www.bilibili.com/video/BV1YZ4y1S72j)
  - links: https://github.com/mli/paper-reading
- **多模态论文串讲·下【论文精读·49】**
  - [B station](https://www.bilibili.com/video/BV1fA411Z772)
  - links: https://github.com/mli/paper-reading