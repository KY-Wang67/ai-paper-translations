# 超越二元奖励：训练语言模型推理自身的不确定性

中文公开修订版 v1.2，2026-11-10。dot 制作的非官方 AI 辅助翻译与重排，不是完整译文。

## 原文与署名

Mehul Damani, Isha Puri, Stewart Slocum, Idan Shenfeld, Leshem Choshen, Yoon Kim, Jacob Andreas. *Beyond Binary Rewards: Training LMs to Reason About Their Uncertainty*. arXiv:2507.16806v2，2026-05-15 修订。

- 具体版本与许可入口：https://arxiv.org/abs/2507.16806v2
- 原论文 PDF：https://arxiv.org/pdf/2507.16806v2
- 原作者项目网页：https://rl-calibration.github.io/
- 原论文许可：https://creativecommons.org/licenses/by/4.0/
- 完整法律文本：https://creativecommons.org/licenses/by/4.0/legalcode.en

## v1.2 恢复范围

- 恢复图 1(b)(c) 的作者统计图及其中文标识解释。图 1(a) 被排除在渲染区域之外，(b)(c) 单独生成新像素图并封装成全新 PDF；没有沿用完整原图的对象、CropBox 隐藏内容或文字层。曲线、坐标、数值与图例不改写。
- 恢复附录 N：SimpleQA 的 2018 年 Jerlov Award 问题、标准答案 Annick Bricaud，以及原论文报告的 RLCR、RLVR 和 Qwen-7B-Base 三段对应模型输出。官方 CSV 的第 2 条数据记录（不计表头）与该问答完全对应。保留模型输出中的事实错误、标签和置信度写法，不作为事实断言。
- 新增独立第三方权利附页、完整 MIT 通知和许可链接；同步修订范围说明，明确恢复和仍未收录内容。

## 仍未恢复

- 图 1(a) 的逐字问题／模型输出示例及原中文逐字对照：具体例子的权利来源本次未核清。
- 附录 O 的 HotpotQA-Modified 问题、Wikipedia 支持段落及相应模型输出：官方明确为 CC BY-SA 4.0，但本次尚未建立每个支持段落的具体 Wikipedia 修订与署名链，因此未恢复。不能把这些素材统一改标为 CC BY 4.0。
- 附录 P 的数学题及相应模型输出：未完成具体题源和许可核验，继续不收录。

上述暂缺不表示认定原论文引用侵权。作者的方法、定理、数学推导、实验表格、统计图、系统提示与参考文献保留；原有图表编号保留，中文重排页码与原文不同。

## 许可边界和改动

原论文内容由原权利人按 CC BY 4.0 直接授权，dot 的翻译与编排贡献亦按 CC BY 4.0 提供。SimpleQA 原问题与标准答案遵循其 MIT 许可；不得用论文或译文的 CC BY 4.0 取代第三方原有许可。具体署名、来源和完整 MIT 通知见 THIRD_PARTY_NOTICES.md 及 PDF 的独立权利附页，完整 CC BY 4.0 和 MIT 文本见 LICENSES/。

改动包括中文翻译、重排、标明的译注、中文图内标识解释、上述删节与恢复，以及图 1(b)(c) 的区域渲染。原作者、机构、会议、OpenAI 和其他数据提供者未审校、认可或为本译文背书。AI 辅助译文可能有误。许可不提供担保；本说明不是法律意见或无侵权保证。

## 本包文件与验证

只提供公开版 PDF、README.md、THIRD_PARTY_NOTICES.md、完整许可文本与 SHA256.json。不含英文原文 PDF、论文源包、LaTeX 源码、完整数据集或被删素材。SHA256.json 为包内其他文件的 SHA-256 清单（不含自身）。

PDF 已完成三轮 XeLaTeX 编译和全部页面渲染审阅。许可链接为可点击 PDF 链接；PDF 嵌入附件数为 0。沿用部分的理论证明、实验章节、全部表格与原有统计图文件经源级一致性检查；新图不含 (a) 的对象或文字层。具体机器检查记录保存在制作工作区，不作为发布素材。

## 在线阅读

[阅读最新 v1.2 PDF](rlcr_zh_public_v1.2.pdf)，43 页。

[第三方权利说明](THIRD_PARTY_NOTICES.md) · [完整许可](LICENSES/)。旧版 v1.1 保留用于历史查阅，当前请使用 v1.2。
