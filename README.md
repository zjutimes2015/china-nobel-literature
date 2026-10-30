# china-nobel-literature

面向中国语境、具有诺贝尔文学奖气质的**原创**中文长篇写作项目（研读公开材料 → 技法笔记 → 原创小说）。

## 版权声明（硬约束）

- **禁止**复制、粘贴、分发任何受版权保护的诺奖作品全文或大段原文。
- **只用**：Nobel Prize 官网公开颁奖词/演讲摘要、公开书目与得主元数据、学术/批评中的技法讨论、本仓原创文字。
- GitHub 上**没有**合法的「诺奖文学全文合集」。上游参考仓是元数据/书目/时间线，不是盗版全文。
- 明确**忽略** `dray1220/nobel-prize-deconstruction`：该仓拆的是诺贝尔**经济学奖**论文，与文学奖无关。

## Fork / 上游清单（元数据，非全文）

本地克隆目录：`/workspace/nobel-upstream/`

| 来源 | 用途 |
|------|------|
| [NobelDB/NobelDB-Data](https://github.com/NobelDB/NobelDB-Data) | 得主与奖项 JSON，含 literature motivation |
| [Pocket-Library](https://github.com/)（书目脚本 + names.txt） | 1901–2021 文学奖得主名单与书目抓取思路 |
| yuanshengxu/-（`nobel-literature-timeline`） | 文学奖时间线入口 |
| [data.nobelprize.org](https://data.nobelprize.org/) | 官方开放数据 |
| Anna-XIE-explorer/nobel-literature-prize | 可视化元数据（可选；fork 若遇 API 限流则仅本地 clone） |

官网权威页见 [`sources.md`](./sources.md)。

## 写作目标

- 气质：地方细节极硬 + 普遍人性；语言有纹理；道德含混（给对手留半步）。
- 产出：原创三卷本《回潮》（见 `novel/vol1|vol2|vol3`），目标 8–12 万汉字；史诗短长篇。
- 技法落地：见 `study/craft-notes.md`。

## 目录

```
china-nobel-literature/
  README.md
  sources.md
  study/          # 研读与技法
  novel/          # 原创长篇
  refs/           # 可选元数据浅克隆
```

## 阅读小说

见 [`novel/README.md`](./novel/README.md)。
