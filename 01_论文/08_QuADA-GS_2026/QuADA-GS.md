---
type: paper
aliases: ["QuADA-GS", "Adaptive Densification for High-Fidelity and Efficient Sparse Gaussian Splatting in Arbitrary-Scale Super-Resolution"]
arxiv: 2606.29400v2
year: 2026
venue: "预印本，未核实会议/期刊录用"
doi: "待核验"
source_pdf: "../../Zotero/data/storage/2NV7G6Y8/Adaptive_Densification_for_High-Fidelity_and_Efficient_Sparse_Gaussian_Splatting_in_Arbitrary-Scale_Super-Resolution.pdf"
zotero_attachment_key: 2NV7G6Y8
source_basis: 此前固定arXiv版本
zotero_key: 4DHVKNFJ
collection: LV8XCQ9B
source_checked: 2026-10-29
delivery: CC BY 4.0版本全文对照
tags: [论文, 图像超分辨率]
---

# QuADA-GS

**Adaptive Densification for High-Fidelity and Efficient Sparse Gaussian Splatting in Arbitrary-Scale Super-Resolution**

作者：Giulio Federico, Giuseppe Amato, Claudio Gennaro, Fabio Carrara, Marco Di Benedetto。发表信息：预印本，未核实会议/期刊录用。

出版物DOI：待核验；保留已核实arXiv ID，不编造出版物DOI。

[此前归档的 arXiv 版本](https://arxiv.org/abs/2606.29400v2) · 在Zotero中选择（溯源地址：`zotero://select/library/items/4DHVKNFJ`） · [完整检索与版本记录](../../PUBLICATION_SCOPE.md)。

对照以所列 CC BY 4.0 固定 arXiv 版本为准。

## 先带着一个问题读

**高斯密度与表示容量应如何按区域分配？**

阅读重点：从均匀分配转向按内容分配高斯、四叉树和稀疏结构的代价；v2根据得分阈值预测扩展层级，不应描述为显式固定全局预算约束。本批固定2026-09-08 v2，是预印本。

学习内容：[逐段中英对照](../../PUBLICATION_SCOPE.md)。制作状态与覆盖边界见该文件和同目录 translation_notes；索引生成不代表全文已经验收。

相关概念：[自适应增密](../../02_%E6%A6%82%E5%BF%B5/%E8%87%AA%E9%80%82%E5%BA%94%E5%A2%9E%E5%AF%86.md)、[二维高斯](../../02_%E6%A6%82%E5%BF%B5/%E4%BA%8C%E7%BB%B4%E9%AB%98%E6%96%AF.md)、[计算量与延迟](../../02_%E6%A6%82%E5%BF%B5/%E8%AE%A1%E7%AE%97%E9%87%8F%E4%B8%8E%E5%BB%B6%E8%BF%9F.md)。

## 关联论文与证据

[GSASR](../06_GSASR_2025/GSASR.md)：回看其直接方法起点，再读 QuADA-GS §3 的改动。 关系分类及原始来源见检索记录；教学顺序不等于文献引用链。

## 本地原始附件

- [此前归档的 arXiv 正文 PDF](../../PUBLICATION_SCOPE.md) · 附件 `2NV7G6Y8` · SHA-256 `e909677854c14d55f8544f55b4a92615337eba5549c2614bff4616ee08816a93`

SI 来源状态：`check_embedded_appendices_in_paper_pdf`。独立SI与正文内嵌SI可能重叠，不计为独立论文。 文件已通过 Zotero 插件及受支持附件接口导入并回读路径/哈希；没有运行作者训练或复现实验。

## 阅读完成自检

- [ ] 能用三句话解释输入、输出与主要变化。
- [ ] 能画出特征或高斯如何到输出像素的流程。
- [ ] 能找到主实验的骨干、数据、退化、倍率、色彩空间及裁边条件。
- [ ] 能解释一个消融实验，同时指出它不能证明什么。

返回 [论文索引](../%E8%AE%BA%E6%96%87%E7%B4%A2%E5%BC%95.md) · [从LIIF到前沿的学习路线](../../00_%E5%AF%BC%E8%88%AA/%E4%BB%8ELIIF%E5%88%B0%E5%89%8D%E6%B2%BF%E7%9A%84%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF.md)。
