# 思维链提示激发大语言模型的推理能力

**中文公开版 v1.1，含定点删节。** dot 制作的 AI 辅助非官方译本，未经原作者审校或背书。中文翻译、图表重排、许可补充及删节均为改动；并非毫无删节的全译，也不保证翻译无误。

## 原作与许可

Jason Wei、Xuezhi Wang、Dale Schuurmans、Maarten Bosma、Brian Ichter、Fei Xia、Ed H. Chi、Quoc V. Le、Denny Zhou。

*Chain-of-Thought Prompting Elicits Reasoning in Large Language Models*，arXiv:2201.11903v6，2023-01-10。

- [具体原文版本](https://arxiv.org/abs/2201.11903v6)
- [原文 CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

中文新增表达在可许可范围内按 CC BY 4.0 提供。第三方材料保留其独立许可，不能将全文件一概理解为仅受 CC BY 4.0 约束。完整 MIT、Apache 2.0 和 AQuA 原始通知同时内置 PDF，并附在 THIRD_PARTY_LICENSES.txt。

## 保留范围

保留研究正文、作者自有方法及统计图、全部公式和统计数据、研究分析、参考文献，以及作者手写数学提示和合成符号任务。保留论文的错误模型输出供研究分析，不视为正确事实。

另外逐项匹配并保留：

- GSM8K 共 23 道唯一例题，包括 FAQ、错误分析及附录题。官方 test.jsonl 的 0 基题序：3、40、55、233、271、285、109、130、42、83、17、71、33、14、191、277、20、2、48、51、58、66、35。Copyright (c) 2021 OpenAI；MIT。[来源与许可](https://github.com/openai/grade-school-math/blob/master/LICENSE)。
- SVAMP 的 DVD 题，官方 SVAMP.json 标识 chal-1。Copyright (c) 2021 Arkil Patel；MIT。[来源与许可](https://github.com/arkilpatel/SVAMP/blob/main/LICENSE)。
- AQuA 四条提示对应 train.json 0 基题序 18、15、19、55；塔题对应 test.json 第 0 项。Copyright 2017 Google Inc.；Apache 2.0。[来源与许可](https://github.com/google-deepmind/AQuA/blob/master/LICENSE)。塔题选项在论文底本中与原数据的括号写法不同，本版保留论文底本并在 PDF 注明，不静默纠正。
- StrategyQA 共 10 道唯一题，BIG-bench task.json 0 基题序 0、1、2、3、5、7、19、21、22、24。Copyright (c) 2021 Elad Segal；原数据 MIT，BIG-bench 分发另保留 Apache 2.0 条件。[原许可](https://github.com/eladsegal/strategyqa/blob/main/LICENSE)；[具体任务](https://github.com/google/BIG-bench/tree/main/bigbench/benchmark_tasks/strategyqa)。
- BIG-bench 日期理解共 10 条，task.json 0 基题序 202、233、249、217、106、360、237、53、143、65。作者 Xinyi Wu、Zijian Wang。[具体任务](https://github.com/google/BIG-bench/tree/main/bigbench/benchmark_tasks/date_understanding)。
- BIG-bench 体育理解共 12 条，task.json 0 基题序 20、23、24、26、6、3、5、1、0、4、8、2。作者 Ethan Kim。[具体任务](https://github.com/google/BIG-bench/tree/main/bigbench/benchmark_tasks/sports_understanding)。Jamel/Jamal 拼写差异按底本保留。
- 上述 BIG-bench 材料采用 [Apache 2.0](https://github.com/google/BIG-bench/blob/main/LICENSE)。题目译为中文并重排；论文作者编写的思维链与模型输出按论文呈现。

## 定点删节

- 图 1：仅删 MultiArith 食堂题的叙事及输出对叙事的复述，保留原数值、算式、模型答案、方法结构与 Roger 网球示例。该具体原始题目授权未完成核验。
- 任务汇总图的 CSQA、SayCan 两个单元格，以及附录 CSQA、SayCan 输入/输出和完整提示表：以明确占位说明代替具体第三方题目、选项与对应输出，保留图表编号及研究统计和分析。CSQA 的可再分发与翻译许可未核清；SayCan 官方将 v0 数据集标为 CC BY 4.0，但此处具体样例的逐项来源未核清，不能据此断言 SayCan 无开放许可。
- 数学数据集概览表：仅删 ASDiv、MAWPS SingleOp、SingleEq、AddSub、MultiArith 五行例题，保留名称与样本量。ASDiv 虽标 CC BY-NC 4.0，但具体教学题目的上游权利链未核清；MAWPS 四题未确认可适用的原始材料授权。

“未核清”是本次发布的保守范围决定，不是对一切使用是否合法的结论。本说明不构成法律意见。原论文许可证一节作为历史陈述保留，并加注以本版末尾实际范围为准。

## 文件范围

仅提供 PDF、此 README、第三方完整许可通知。没有英文原文 PDF、未审源码包、数据集副本或嵌入附件；删节内容不会借原图、源码或附件一并分发。

核验日期：2026-11-10。
