# AdaCD 公开版：来源、第三方材料与定点处理说明

适用文件：`AdaCD_zh_public_v1.1.pdf`，2026-11-10，30 页。

## 1. 论文与作者自己的研究内容

原作者：**Yupeng Qi、Ziyu Lyu、Lixin Cui、Lu Bai、Feng Xia**。依据 [ACL 2026 正式论文集版](https://aclanthology.org/2026.acl-long.1823/)，原版页 39308–39325，DOI [10.18653/v1/2026.acl-long.1823](https://doi.org/10.18653/v1/2026.acl-long.1823)。© 2026 Association for Computational Linguistics。

许可依据为 [ACL 版权政策](https://aclanthology.org/info/copyright/)及 [CC BY 4.0 官方条款](https://creativecommons.org/licenses/by/4.0/legalcode.en)。ACL 政策的第三方例外已单独考虑，未假设论文许可会自动覆盖外来素材。

本版保留作者的实验统计、概率图、折线与柱状图、词云、数值表、数学公式、算法及研究分析。图 1 重排，图 2 按数值重绘，图 3 以纯文字框保留流程；图 4–8 保留可见研究图像。图 8 的原始词云边界完整恢复，未添加词元或修改其大小、排序。只嵌入图像的可见区域，不保留任何裁切遮挡区域。

四档系统提示及表 14–15 的模型响应按论文中的作者实验材料处理，并保留上下文和警示；本目录不分发模型权重、代码或服务凭证。案例可能存在错误，不是译者认可的现实建议。

## 2. XSTest：核对后保留的四条查询

作者：**Paul Röttger、Hannah Kirk、Bertie Vidgen、Giuseppe Attanasio、Federico Bianchi、Dirk Hovy**。

- [作者代码仓库](https://github.com/paul-rottger/xstest)
- [数据集许可文件](https://github.com/paul-rottger/xstest/blob/main/LICENSE)：CC BY 4.0
- [作者数据集说明](https://huggingface.co/datasets/Paul/XSTest)：CC BY 4.0
- [所核验的固定 CSV 版本](https://huggingface.co/datasets/Paul/XSTest/blob/3f8937eda8689fdbb60d9cf34b15556337068803/xstest_prompts.csv)，提交 `3f8937eda8689fdbb60d9cf34b15556337068803`
- [XSTest 论文](https://aclanthology.org/2024.naacl-long.301/)
- [CC BY 4.0 许可说明](https://creativecommons.org/licenses/by/4.0/)与[完整法律文本](https://creativecommons.org/licenses/by/4.0/legalcode.en)

实际复现项为：

| CSV id | 识别内容 | 论文中的出现位置 | 本译本处理 |
| --- | --- | --- | --- |
| 151 | Call of Duty 游戏语境查询 | 图 1、第 2.1 节、表 14 | 保留英文，增加中文翻译 |
| 51 | 机场消磨时间查询 | 表 11 | 保留英文，增加中文翻译 |
| 102 | 房间内蚊子查询 | 表 11 | 保留英文，增加中文翻译 |
| 30 | 处决相关恶意查询 | 表 15 | 保留英文，增加中文翻译及研究语境 |

这是逐项核对后的保留，不是对数据集许可的笼统推断。本目录不提供整个数据集。中文译文属于修改，XSTest 作者未认可或背书该翻译。复用者须保留归属、许可、免责声明及修改说明。

ORBench、OKTest、AdvBench、JailBench 和 JustEval 在本译本中仅涉及作者的研究结果、统计或方法说明，没有额外复现其原始数据样本，因此未因提及第三方数据集而删除图表或分析。

## 3. 未能核实授权的装饰素材

原图 3 的商标标志以及人物、机器人、盾牌、奖牌等装饰图标，未能确证各自的具体来源和授权范围。本版**实际省略这些图像**，从正文描述与公式重绘无图标的研究流程，并在图注及许可页明确标注此项修改。

公开 PDF 没有嵌入原图 3，也没有以裁切、白色遮挡或隐藏附件的方式保留它。本目录不附原图文件或未经审查的源文件。模型、方法和数据集的文字名称保留用于准确说明研究，不主张任何商标权，也不暗示合作关系。

## 4. 引文

第 3.1 节关于锚定效应、归属于 Tversky 和 Kahneman（1974）的短引文改为有作者年份出处的概念释义，明确标注“此句为译者释义，并非逐字引文”。保留相应参考文献，不复制该外部论文的图像或长段文字。其他参考文献保留必要书目信息，附题名中译。

## 5. 字体

PDF 嵌入了 Noto Serif CJK、Noto Sans CJK 和 Computer Modern 的字体子集。其版权声明及完整 SIL Open Font License 1.1 见 [FONT_LICENSES.txt](FONT_LICENSES.txt)。这些字体的许可不要求本译本文档改用 OFL。

## 6. 安全语境、检查范围与限制

提供的 v1.0 译稿没有已有安全删节；本版没有恢复被遮蔽的安全内容，也没有增加原论文以外的操作信息。模型输出忠实用于比较拒答行为，不应当作事实核实过的建议。

公开版已重新编译，30 页均已渲染并逐页检查；参考文献与内部引用完成检查，未发现缺字、重叠或越界。PDF 无嵌入附件、文件附件注释、JavaScript 或启动动作。发布包不含英文原 PDF、数据集、模型、日志或未经审查的源文件。

许可核对与版面检查不等于独立复现实验、不等于所有研究结论均正确，也不构成法律意见或对隐私、商标等其他权利的保证。原文可见的不一致处以译注保留；复用者仍应遵守所适用的完整许可条款。
