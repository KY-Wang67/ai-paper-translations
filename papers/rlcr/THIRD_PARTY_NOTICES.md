# 第三方权利与署名通知

核验日期：2026-11-10。适用文件：rlcr_zh_public_v1.2.pdf。

## 1. 原论文及作者统计图、模型输出

**作品**：Beyond Binary Rewards: Training LMs to Reason About Their Uncertainty，arXiv:2507.16806v2。

**作者**：Mehul Damani, Isha Puri, Stewart Slocum, Idan Shenfeld, Leshem Choshen, Yoon Kim, Jacob Andreas。

**官方来源**：https://arxiv.org/abs/2507.16806v2 。

**许可**：Creative Commons Attribution 4.0 International，https://creativecommons.org/licenses/by/4.0/ ，完整法律文本 https://creativecommons.org/licenses/by/4.0/legalcode.en ，本包副本 LICENSES/CC-BY-4.0.txt。

**使用与改动**：中文翻译、重排、明确标识的译注、图内标识中文解释和公开版范围删节。v1.2 从图 1 中单独保留 (b)(c) 的作者统计图，并恢复原论文报告的 SimpleQA 三段对应模型输出。图 1(b)(c) 按原坐标、曲线、数值和标识渲染成新图；未将图 1(a) 的任何原图对象带入新 PDF。原图 1(a) 及附录 O、P 的逐字内容继续删节。除标明的译注外，不改写作者实验表格和理论公式。

原论文许可只覆盖原权利人可授权的内容，不自动覆盖论文内任何第三方素材。dot 的翻译与排版贡献按 CC BY 4.0 提供，不能替代第三方素材原有许可。

## 2. SimpleQA 问题与标准答案（附录 N）

**权利通知**：Copyright (c) 2024 OpenAI。

**官方许可依据**：OpenAI simple-evals README 的 Evals 节明确将 SimpleQA 标为 MIT。

- https://github.com/openai/simple-evals/blob/main/README.md#evals
- https://github.com/openai/simple-evals/blob/main/LICENSE
- 官方评测实现及数据链接：https://github.com/openai/simple-evals/blob/main/simpleqa_eval.py
- 官方数据 CSV：https://openaipublic.blob.core.windows.net/simple-evals/simple_qa_test_set.csv

**精确对应**：CSV 第 2 条数据记录（不计表头，零基索引 1）的问题为 “Who was awarded the Oceanography Society's Jerlov Award in 2018?”，标准答案为 “Annick Bricaud”。PDF 收录其中文译文。数据表共 4,326 条记录，核验下载文件 SHA-256：feee3f7e7db3617e94e8fcf1977b756ec420ef8568f4e0fcbbe0e92e9d5fc032。

只采用该问答，不复制该记录 metadata 指向的网站文章或 Wikipedia 段落。论文所报告的 RLCR、RLVR、Qwen-7B-Base 对应模型输出依原论文许可翻译，保留其错误答案及置信度，不是 OpenAI 数据集的标准答案。

**完整 MIT 版权及许可通知**（同时置于 PDF 前置权利页及 LICENSES/MIT-SimpleQA.txt）：

MIT License

Copyright (c) 2024 OpenAI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 3. 尚未恢复的第三方材料

HotpotQA 官方主页 https://hotpotqa.github.io/ 明确声明数据集 CC BY-SA 4.0；官方 Wikipedia 处理说明 https://hotpotqa.github.io/wiki-readme.html 明确声明其预处理语料也采用 CC BY-SA 4.0，并标注英文 Wikipedia 转储日期为 2017-10-01。官方资料归属说明可用于许可方向判断，但不能替代本例每段文本的具体来源、修订和署名核查。本次未完成该逐段链条，因此附录 O 的逐字内容和对应模型输出未恢复，也没有在本包中将其再许可为 CC BY 4.0。

图 1(a) 的逐字示例和附录 P 的具体数学题同样没有在本次完成题源与许可核查，因此继续不收录。未收录不表示认定原论文引用侵权。

## 4. 非官方译文与不背书

本译文为 dot 制作的非官方 AI 辅助中文翻译与重排。原作者、所属机构、会议、OpenAI 和其他数据提供者未审校、认可或为本译文背书。已注明的中文翻译和编辑改动不代表他们的观点。模型生成的错误内容用于呈现原论文实验，不作事实断言。许可不提供担保，本发布核查说明不是法律意见或无侵权保证。
