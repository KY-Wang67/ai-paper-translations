# 第三方材料与许可通知

核验日期：2026-11-10。版本：Self-Consistency 中文公开恢复版 1.2。

## 1. 原论文与译文

Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed H. Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou. *Self-Consistency Improves Chain of Thought Reasoning in Language Models*. ICLR 2023. [arXiv:2203.11171v4](https://arxiv.org/abs/2203.11171v4)，2023-03-07。

该版本 arXiv 页面链接到 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。[法律文本](https://creativecommons.org/licenses/by/4.0/legalcode.en)；本包副本：`LICENSES/CC-BY-4.0.txt`。

dot 的非官方 AI 辅助中文翻译、重排及编辑说明在可许可范围内采用 CC BY 4.0，但不包括下面明确标注的 MIT / CC BY-SA 材料。原作者未审校或认可本译文。

相较原文的改动：中文翻译，字体、分页与标点调整，AQuA 统计图边界修复以显示被裁切的图例，明确标注的逐字实例删节。本次相较 1.1 恢复原表 13 的 GSM8K 一行、原表 15 的四条 ARC 问答、正文鸭蛋题模型输出引文，并增加分项权利与 MIT 通知。保留原模型错误，不重算或重绘统计数据。

## 2. GSM8K / OpenAI：MIT

**Copyright (c) 2021 OpenAI**

官方来源：
- [OpenAI GSM8K 数据卡，MIT](https://huggingface.co/datasets/openai/gsm8k)
- [官方仓库 MIT 全文](https://github.com/openai/grade-school-math/blob/master/LICENSE)
- [官方 test.jsonl](https://github.com/openai/grade-school-math/blob/master/grade_school_math/data/test.jsonl)

具体对应：
- 原表 13 的 Kyle 购书题：官方 `grade_school_math/data/test.jsonl` 第 25 行（从 1 计数），最终答案 26。
- 正文鸭蛋题的模型输出引文：基于同文件第 1 行 Janet 题，标准答案 18。图 1 同时含未核验的停车场提示，因此未恢复整个混合来源图。

许可边界：数据题干及相应中文翻译保留 MIT。论文所列贪心/采样推理是论文作者报告的模型输出，并非 GSM8K 官方答案，按论文上游 CC BY 4.0 归属。完整 MIT 通知收录于 `LICENSES/gsm8k-MIT.txt`，亦完整置于 PDF 权利附页，随副本一同提供。

## 3. ARC / Allen Institute for Artificial Intelligence：CC BY-SA 4.0

数据集：AI2 Reasoning Challenge (ARC)，Allen Institute for Artificial Intelligence（Ai2）。

数据集署名：Peter Clark, Isaac Cowhey, Oren Etzioni, Tushar Khot, Ashish Sabharwal, Carissa Schoenick, Oyvind Tafjord. *Think you have Solved Question Answering? Try ARC, the AI2 Reasoning Challenge*. 2018. [arXiv:1803.05457](https://arxiv.org/abs/1803.05457)。

许可证据：Ai2 官方账户的[数据卡](https://huggingface.co/datasets/allenai/ai2_arc)与[原始元数据](https://huggingface.co/datasets/allenai/ai2_arc/raw/main/README.md)明确标为 `cc-by-sa-4.0`。不是从代码许可推断题目许可。

原表 15 逐条对应，顺序和答案键均核对：
1. 搓手题：ARC-Challenge / train，`Mercury_SC_415702`，A。
2. 发烧题：ARC-Easy / train，`Mercury_7220990`，B。
3. 凝固题：ARC-Easy / train，`Mercury_7205118`，C。
4. 电路开关题：ARC-Easy / train，`Mercury_SC_401169`，D。

官方记录：[Challenge/train](https://huggingface.co/datasets/allenai/ai2_arc/viewer/ARC-Challenge/train)，[Easy/train](https://huggingface.co/datasets/allenai/ai2_arc/viewer/ARC-Easy/train)。

**清楚隔离的改编块：原表 15 的四组中文问答编译整体采用 CC BY-SA 4.0。** 上游 ARC 题干、选项和答案键为 CC BY-SA 4.0，其中文翻译亦为 CC BY-SA 4.0。表内手写思维链原材料出自 Wang 等人的论文，原文附录 A.3 明确说明其自行编写，原材料上游许可仍为 CC BY 4.0，不被本改编块的许可替换。整份 PDF 是分项许可合集，并未统一重新许可为 CC BY-SA 或 CC BY。

改动：英文题目、选项及手写思维链翻译为中文，选项标签改为小写，标点及布局调整；题序、选项顺序、答案键保持。未纠正原提示中的科学简化。

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)，[法律文本](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en)。本包副本：`LICENSES/CC-BY-SA-4.0.txt`。分享及改编此块须保留署名、许可、变更说明，并遵守同方式共享，不施加额外限制。

## 4. 许可副本与免责

MIT 文本从 OpenAI 官方仓库原样保留。CC 完整文本副本来自 SPDX 的标准许可证文本：[CC BY 4.0](https://github.com/spdx/license-list-data/blob/main/text/CC-BY-4.0.txt)，[CC BY-SA 4.0](https://github.com/spdx/license-list-data/blob/main/text/CC-BY-SA-4.0.txt)；对应官方法律文本链接见各节。

各材料版权及相关权利属于相应权利人。原作者、Ai2、OpenAI、会议及其他所属机构未审校或认可本译文。没有担保。本说明不是法律意见，不限制法律给予的例外与限制。本包不包含原文、源码或数据集文件。
