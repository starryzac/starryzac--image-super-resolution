---
type: paper
aliases: ["SRNO", "Super-Resolution Neural Operator"]
arxiv: 2303.02584v1
year: 2023
venue: "CVPR 2023"
doi: "10.1109/CVPR52729.2023.01750"
source_pdf: "../../Zotero/data/storage/9HK6QMQJ/Wei和Zhang - 2023 - Super-Resolution Neural Operator.pdf"
zotero_attachment_key: 9HK6QMQJ
source_basis: 用户提供会议版正文
zotero_key: ETWG2URJ
collection: LV8XCQ9B
source_checked: 2026-10-29
delivery: 用户提供会议版正文逐段中英对照；验收见交付记录
tags: [论文, 图像超分辨率]
---

# SRNO

**Super-Resolution Neural Operator**

作者：Min Wei, Xuesong Zhang。发表信息：CVPR 2023。

出版物DOI：10.1109/CVPR52729.2023.01750。

[此前归档的 arXiv 版本](https://arxiv.org/abs/2303.02584v1) · 在Zotero中选择（溯源地址：`zotero://select/library/items/ETWG2URJ`） · [完整检索与版本记录](../../PUBLICATION_SCOPE.md)。

本轮对照以用户直接提供的 CVPR 会议版 PDF 为准，保留原权利信息；转换依据是用户提供文本，不将该版本标作 CC BY。此前归档的 arXiv 版本仍保留，用于版本核对。

## 先带着一个问题读

**能否把超分辨率理解成函数之间的映射？**

阅读会议版正文第1–5页的算子视角与方法。原有arXiv版附录A–D和独立SI另存，未纳入本轮会议版正文翻译。SRNO用非局部核积分/注意力更新表示；“连续算子”在实现中仍需有限离散。

学习内容：[逐段中英对照](../../PUBLICATION_SCOPE.md)。制作状态与覆盖边界见该文件和同目录 translation_notes；索引生成不代表全文已经验收。

相关概念：[神经算子](../../02_%E6%A6%82%E5%BF%B5/%E7%A5%9E%E7%BB%8F%E7%AE%97%E5%AD%90.md)、[注意力](../../02_%E6%A6%82%E5%BF%B5/%E6%B3%A8%E6%84%8F%E5%8A%9B.md)、[隐式神经表示](../../02_%E6%A6%82%E5%BF%B5/%E9%9A%90%E5%BC%8F%E7%A5%9E%E7%BB%8F%E8%A1%A8%E7%A4%BA.md)。

## 关联论文与证据

[GSASR](../06_GSASR_2025/GSASR.md)：同一任务的不同表示路线；用于比较建模视角，不宣称直接继承。 关系分类及原始来源见检索记录；教学顺序不等于文献引用链。

## 本地原始附件

- [此前归档的 arXiv 正文 PDF](../../PUBLICATION_SCOPE.md) · 附件 `R3I4WNGB` · SHA-256 `88ec768584ec50a89132a3bce611b7886f888981247ca26bf2c038b6bf768727`
- [补充 PDF](../../PUBLICATION_SCOPE.md) · 附件 `TERITYFF` · SHA-256 `1801726faee17dbbcde16cea65c5fd6e17f8080fe75e71255c5ccdec1977a0f9`
- [用户提供的会议版正文 PDF（本轮对照来源）](../../PUBLICATION_SCOPE.md) · 附件 `9HK6QMQJ` · SHA-256 `ee1fd2a52d056827af200649c7b2a0266a9cde4543434b99e11167c4f919b266`

SI 来源状态：`standalone_published_supplement_included`。本轮只翻译用户提供的会议版正文；原有独立 SI 已归档，尚未做逐段对照。 文件已通过 Zotero 插件及受支持附件接口导入并回读路径/哈希；没有运行作者训练或复现实验。

## 阅读完成自检

- [ ] 能用三句话解释输入、输出与主要变化。
- [ ] 能画出特征或高斯如何到输出像素的流程。
- [ ] 能找到主实验的骨干、数据、退化、倍率、色彩空间及裁边条件。
- [ ] 能解释一个消融实验，同时指出它不能证明什么。

返回 [论文索引](../%E8%AE%BA%E6%96%87%E7%B4%A2%E5%BC%95.md) · [从LIIF到前沿的学习路线](../../00_%E5%AF%BC%E8%88%AA/%E4%BB%8ELIIF%E5%88%B0%E5%89%8D%E6%B2%BF%E7%9A%84%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF.md)。
