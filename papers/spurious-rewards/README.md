# Spurious Rewards：重新思考 RLVR 的训练信号

原题：Spurious Rewards: Rethinking Training Signals in RLVR。
原作者：Rulin Shao、Shuyue Stella Li、Rui Xin、Scott Geng、Yiping Wang、Sewoong Oh、Simon Shaolei Du、Nathan Lambert、Sewon Min、Ranjay Krishna、Yulia Tsvetkov、Hannaneh Hajishirzi、Pang Wei Koh、Luke Zettlemoyer。

## 实际版本与许可

中文公开删节版 v1.1，2026-11-10。底本为 ICML 2026 / PMLR 306:110167–110207 的41页正式版。

- 官方论文页：https://proceedings.mlr.press/v306/shao26d.html
- PMLR出版协议：https://proceedings.mlr.press/pmlr-license-agreement.html
- ICML2026官方作者指南：https://icml.cc/Conferences/2026/AuthorInstructions

ICML2026作者指南的Consent forms部分要求提交PMLR出版协议。该协议第2条将论文以CC BY 4.0许可公众使用，第3条要求注明原出版物并链接原论文PMLR页面。此版据此使用CC BY 4.0，作者保留版权。

**版本不能混用：** arXiv:2506.10947v2 的页面列示 CC BY-NC-SA 4.0（https://arxiv.org/abs/2506.10947v2）；那不是本译本的发布许可依据。不能把该早期版本的非商业/相同方式共享条件误写为PMLR正式版的许可，也不能反过来用本说明重新许可其他版本。

## 内容与删节

本版不是全文译本。保留研究正文、数学推导、实验数据、统计图、参考文献及作者分析。改动包括翻译、重排、图内标记中文对照、明确标记的译注、重复图表锚点修复和以下公开发布删节：

1. 正文缩略代码推理实例的逐字题目和输出。
2. 末尾九个完整定性实例的题目、代码和模型逐字输出，包括原始数学题、数值扰动和叙述改写版本。
3. 提示比较表中的完整原始提示串及其逐字中文转写，包含其他研究的提示模板与占位文本。

这些数据集/模板材料的独立再传播许可尚未逐项核实。被移除图表保留编号占位；研究分析和统计结果未删除。PDF不附被移除实例、英文原文或源文件。

## 再传播与核查范围

本稿是 dot 制作的非官方 AI 辅助中文翻译与重新排版。原作者、机构及会议未审校或认可译文。译文的翻译与排版贡献同以 CC BY 4.0 提供，原作由原权利人按其许可直接授权；本译文不替换原权利或原有通知。

- 许可：https://creativecommons.org/licenses/by/4.0/
- 法律文本：https://creativecommons.org/licenses/by/4.0/legalcode.en
- 再传播时保留原作者、原题、出版来源或具体版本、原文链接及许可链接，注明翻译、重排、译注、删节和后续改动。不得暗示原作者认可。
- 独立代码、模型、数据集、软件库及第三方图文适用各自权利，不能仅凭论文许可一并复制。
- 本公开目录仅包含译文 PDF 与说明，不附英文原文、论文源档案或软件代码。

本次核查基于官方许可和可见文件内容，不是法律意见或无侵权保证。未收录材料的许可仍可后续单独核实；删节不表示认定原论文的引用侵权。

## 文件

[阅读中文公开删节版 PDF](spurious_zh_public_v1.1.pdf)，40 页。
