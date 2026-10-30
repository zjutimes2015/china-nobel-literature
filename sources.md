# 公开可核验来源（sources）

本项目只引用诺贝尔奖官网公开材料、书目/元数据仓、以及批评/技法讨论。**不收录、不转载任何受版权保护的小说全文。**

## 官方颁奖词 / 新闻稿 / 演讲

1. 莫言 2012 新闻稿（委员会理由）：https://www.nobelprize.org/prizes/literature/2012/press-release/
2. 莫言 2012 授奖辞（Per Wästberg）：https://www.nobelprize.org/prizes/literature/2012/ceremony-speech/
3. 莫言 2012 诺贝尔演讲页：https://www.nobelprize.org/prizes/literature/2012/yan/lecture/
4. 莫言 2012 晚宴致辞（中/英）：https://www.nobelprize.org/prizes/literature/2012/yan/speech/ ；中文 PDF：https://www.nobelprize.org/uploads/2018/06/yan-speech_ch.pdf
5. 高行健 2000 新闻稿（含作品讨论摘要）：https://www.nobelprize.org/prizes/literature/2000/press-release/
6. 高行健 Facts：https://www.nobelprize.org/prizes/literature/2000/gao/facts/
7. 阿列克谢耶维奇 2015 新闻稿：https://www.nobelprize.org/prizes/literature/2015/press-release/
8. 大江健三郎 1994 新闻稿：https://www.nobelprize.org/prizes/literature/1994/press-release/
9. 韩江 2024 新闻稿：https://www.nobelprize.org/prizes/literature/2024/press-release/
10. 韩江 2024 诺贝尔演讲：https://www.nobelprize.org/prizes/literature/2024/han/lecture/
11. 加西亚·马尔克斯 1982 新闻稿：https://www.nobelprize.org/prizes/literature/1982/press-release/
12. 韩江 2024 书目/小传 PDF：https://www.nobelprize.org/uploads/2024/10/bio-bibliography-literatureprize2024.pdf
13. 诺奖课程讲稿（韩江，教学用）：https://www.nobelprize.org/uploads/2024/10/Speakersmanuscript_Literature_2024_NobelPrizeLessons.pdf

## 技法/批评讨论（非全文）

14. 刘再复论高行健与莫言对照（普遍性 vs 地方性、语言质地）：https://ctexp.substack.com/p/liu-zaifu-a-comparison-between-nobel
15. 《纽约客》关于莫言与「诺奖情结」的评论：https://www.newyorker.com/books/page-turner/mo-yan-and-chinas-nobel-complex
16. Carnegie 评阿列克谢耶维奇复调非虚构：https://carnegieendowment.org/posts/2015/10/chronicling-a-catastrophe-the-nobel-prize-and-svetlana-alexievich
17. 诺奖官网论大江健三郎：https://www.nobelprize.org/prizes/literature/1994/oe/article/

## 元数据 / 书目型 GitHub（合法参考，非盗版全文）

18. 官方开放数据：https://data.nobelprize.org/
19. Anna-XIE-explorer/nobel-literature-prize（1901–2024 可视化元数据）：https://github.com/Anna-XIE-explorer/nobel-literature-prize
20. NobelDB/NobelDB-Data（结构化 JSON 元数据）：https://github.com/NobelDB/NobelDB-Data
21. metaphacts/nobel-prize（SPARQL/RDF 数据包说明）：https://github.com/metaphacts/nobel-prize

> 说明：本仓 `refs/` 下可放置上述元数据仓的 shallow clone，仅作书目与理由字段学习。若上游含任何版权正文，一律不复制进 `novel/`。

## 本地上游克隆（/workspace/nobel-upstream/）

- `NobelDB-Data/`：得主与奖项结构化元数据（含文学奖 motivation 字段）
- `Pocket-Library/`：诺奖文学得主书目抓取脚本 + names.txt（1901–2021 名单）
- `nobel-literature-timeline/`：文学奖时间线说明（yuanshengxu/-）
- **完全忽略** `nobel-prize-deconstruction/`（及 GitHub 上 dray1220/nobel-prize-deconstruction）：该仓拆的是诺贝尔**经济学奖**论文，与文学奖无关，研读时勿用

本项目研读以官网颁奖词 + 上述元数据/书目仓为准，不依赖、不复制任何小说全文。
