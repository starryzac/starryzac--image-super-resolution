---
type: paper
aliases: ["GSASR", "Generalized and Efficient 2D Gaussian Splatting for Arbitrary-scale Super-Resolution"]
arxiv: 2501.06838v5
year: 2025
venue: "ICCV 2025"
doi: "待核验"
source_pdf: "../../Zotero/data/storage/YFTK7ITK/Generalized_and_Efficient_2D_Gaussian_Splatting_for_Arbitrary-scale_Super-Resolution.pdf"
zotero_attachment_key: YFTK7ITK
source_basis: 此前固定arXiv版本
zotero_key: 8ZP8LVBQ
collection: LV8XCQ9B
source_checked: 2026-10-29
delivery: CC BY 4.0版本全文对照
tags: [论文, 图像超分辨率]
---

# GSASR

**Generalized and Efficient 2D Gaussian Splatting for Arbitrary-scale Super-Resolution**

作者：Du Chen, Liyi Chen, Zhengqiang Zhang, Lei Zhang。发表信息：ICCV 2025。

出版物DOI：待核验；保留已核实arXiv ID，不编造出版物DOI。

[此前归档的 arXiv 版本](https://arxiv.org/abs/2501.06838v5) · 在Zotero中选择（溯源地址：`zotero://select/library/items/8ZP8LVBQ`） · [完整检索与版本记录](../../PUBLICATION_SCOPE.md)。

对照以所列 CC BY 4.0 固定 arXiv 版本为准。

## 先带着一个问题读

**如何预测高斯并高效渲染到任意分辨率？**

阅读重点：可泛化的高斯预测、可微光栅化、速度质量权衡；arXiv v5共26页，含15页整合补充。

学习内容：[逐段中英对照](../../PUBLICATION_SCOPE.md)。制作状态与覆盖边界见该文件和同目录 translation_notes；索引生成不代表全文已经验收。

相关概念：[高斯泼溅与光栅化](../../02_%E6%A6%82%E5%BF%B5/%E9%AB%98%E6%96%AF%E6%B3%BC%E6%BA%85%E4%B8%8E%E5%85%89%E6%A0%85%E5%8C%96.md)、[计算量与延迟](../../02_%E6%A6%82%E5%BF%B5/%E8%AE%A1%E7%AE%97%E9%87%8F%E4%B8%8E%E5%BB%B6%E8%BF%9F.md)、[二维高斯](../../02_%E6%A6%82%E5%BF%B5/%E4%BA%8C%E7%BB%B4%E9%AB%98%E6%96%AF.md)。

## 关联论文与证据

[QuADA-GS](../08_QuADA-GS_2026/QuADA-GS.md)：明确方法联系：QuADA-GS §3采用 GSASR 初始架构并改造增密分配。 关系分类及原始来源见检索记录；教学顺序不等于文献引用链。

## 本地原始附件

- [此前归档的 arXiv 正文 PDF](../../PUBLICATION_SCOPE.md) · 附件 `YFTK7ITK` · SHA-256 `1a3734aec741ff76cac936b5c5ebe7c3af5affca355e3a7f9f603072fcce5a4b`
- [补充 PDF](../../PUBLICATION_SCOPE.md) · 附件 `XRUG25L7` · SHA-256 `92064ad1adcce7550652922a0aacd64a135c62880baa4ea21348361af8b305d0`

SI 来源状态：`standalone_published_supplement_included`。独立SI与正文内嵌SI可能重叠，不计为独立论文。 文件已通过 Zotero 插件及受支持附件接口导入并回读路径/哈希；没有运行作者训练或复现实验。

## 阅读完成自检

- [ ] 能用三句话解释输入、输出与主要变化。
- [ ] 能画出特征或高斯如何到输出像素的流程。
- [ ] 能找到主实验的骨干、数据、退化、倍率、色彩空间及裁边条件。
- [ ] 能解释一个消融实验，同时指出它不能证明什么。

返回 [论文索引](../%E8%AE%BA%E6%96%87%E7%B4%A2%E5%BC%95.md) · [从LIIF到前沿的学习路线](../../00_%E5%AF%BC%E8%88%AA/%E4%BB%8ELIIF%E5%88%B0%E5%89%8D%E6%B2%BF%E7%9A%84%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF.md)。
