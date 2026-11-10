# 自一致性提升语言模型的思维链推理能力

中文公开恢复版 1.2 · 2026-11-10

非官方 AI 辅助中文翻译与编排：dot。原作者、数据集提供方、会议及所属机构未审校或认可本译文。本版仍是选择性收录的公开版，不是完整译文。

## 文件

- `self_consistency_zh_public_v1.2.pdf`：译文，附公开范围、分项版权与第三方权利附页。
- `THIRD_PARTY_NOTICES.md`：来源、署名、逐项恢复位置与许可边界。
- `LICENSES/`：MIT、CC BY 4.0、CC BY-SA 4.0 完整许可文本。
- `SHA256.json`：上述交付文件的 SHA-256 校验值。

本包不含原论文 PDF、论文源码、译文源码、数据集文件或源文件嵌入。

## 本次恢复

1. 原表 13：仅恢复 GSM8K 的 Kyle 购书题一行及论文列出的三条 PaLM-540B 输出，不是恢复整张混合数据集表。
2. 原表 15：恢复 ARC 四条少样本问答；该表的中文编译整体明确标为 CC BY-SA 4.0。
3. 正文第 2 节：恢复基于 GSM8K Janet 鸭蛋题的模型输出引文。

方法、公式、实验数据表、作者统计图、计算资源说明、参考文献均继续保留。原图英文轴标与图例保留，前置页提供中文对照；AQuA 统计图延续前版的边界修复以显示完整图例。

## 仍未收录

- 图 1 整图及完整文字对照：同时含已核为 GSM8K 的鸭蛋题和尚未核验来源的停车场提示，不能仅凭部分 MIT 材料恢复整图。
- 正文停车场逐字示例、正文示例表 4（原 `tab:example_path`）。
- 原表 12、原表 13 除 GSM8K 外的行。
- 原表 14 与原表 16–21 等其他完整提示集。

未收录仅表示本轮没有完成逐项许可核验，不表示认定原有引用侵权。表号沿用原文，按需保留占位；中文重排页码不同于原文。

## 许可

这是分项许可的合集，**不能笼统称整份 PDF 采用单一 CC BY 4.0**：

- 原论文作者的论述、模型输出、实验结果、统计图及相应译文和编排：CC BY 4.0，下述例外除外。
- GSM8K 题干及其中文翻译：保留 MIT 许可和 Copyright (c) 2021 OpenAI；MIT 全文同时嵌于 PDF 权利附页及本包。
- ARC 题干、选项、答案键及其中文改编：CC BY-SA 4.0。表 15 四组问答的中文编译整体也采用 CC BY-SA 4.0，以便整体复用。论文作者手写思维链的上游 CC BY 4.0 许可不被替换。

复制或改编应保留相应署名、许可与变更说明；无担保。本说明不是法律意见，不限制法定例外或许可授予的权利。详见 THIRD_PARTY_NOTICES.md。

## 底本

Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed H. Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou. *Self-Consistency Improves Chain of Thought Reasoning in Language Models*. ICLR 2023. arXiv:2203.11171v4，2023-03-07。

- [论文版本页](https://arxiv.org/abs/2203.11171v4)
- [原论文 PDF](https://arxiv.org/pdf/2203.11171v4)
- [官方源文件](https://arxiv.org/src/2203.11171v4)
- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## 在线阅读

[阅读最新 v1.2 PDF](self_consistency_zh_public_v1.2.pdf)，28 页。

[第三方权利说明](THIRD_PARTY_NOTICES.md) · [完整许可](LICENSES/)。旧版 v1.1 保留用于历史查阅，当前请使用 v1.2。
