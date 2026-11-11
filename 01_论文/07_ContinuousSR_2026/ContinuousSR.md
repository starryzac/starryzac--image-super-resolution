---
type: paper
aliases: ["ContinuousSR", "Pixel to Gaussian: Ultra-Fast Continuous Super-Resolution with 2D Gaussian Modeling"]
arxiv: 2503.06617v1
year: 2026
venue: "ICLR 2026（发表身份）；本地为2025 arXiv v1技术报告"
doi: "待核验"
source_pdf: "../../Zotero/data/storage/I25NTBDT/Pixel_to_Gaussian_Ultra-Fast_Continuous_Super-Resolution_with_2D_Gaussian_Modeling.pdf"
zotero_attachment_key: I25NTBDT
source_basis: 此前固定arXiv版本
zotero_key: LJBY5JZ5
collection: LV8XCQ9B
source_checked: 2026-10-29
delivery: 原创中文导读；完整对照待用户提供原文
tags: [论文, 图像超分辨率]
---

# ContinuousSR

**Pixel to Gaussian: Ultra-Fast Continuous Super-Resolution with 2D Gaussian Modeling**

作者：Long Peng, Anran Wu, Wenbo Li, Peizhe Xia, Xueyuan Dai, Xinjie Zhang, Xin Di, Haoze Sun, Renjing Pei, Yang Wang, Yang Cao, Zheng-Jun Zha。发表信息：ICLR 2026（发表身份）；本地为2025 arXiv v1技术报告。

出版物DOI：待核验；保留已核实arXiv ID，不编造出版物DOI。

[此前归档的 arXiv 版本](https://arxiv.org/abs/2503.06617v1) · 在Zotero中选择（溯源地址：`zotero://select/library/items/LJBY5JZ5`） · [完整检索与版本记录](../../PUBLICATION_SCOPE.md)。

当前为原始 PDF 与原创导读；尚无完整逐段中英对照。

## 先带着一个问题读

**显式高斯表示怎样降低输出网格的生成成本？**

本地附件是2025年3月 arXiv v1技术报告；其连续高斯表示结合位置调整，关注快速渲染。第1页、方法和附录用于读表示/实现，第18页结束。ICLR 2026发表信息不意味着这个附件就是最终稿。

学习内容：[原创学习导读](%E5%AD%A6%E4%B9%A0%E5%AF%BC%E8%AF%BB.md)。制作状态与覆盖边界见该文件和同目录 translation_notes；索引生成不代表全文已经验收。

相关概念：[高斯泼溅与光栅化](../../02_%E6%A6%82%E5%BF%B5/%E9%AB%98%E6%96%AF%E6%B3%BC%E6%BA%85%E4%B8%8E%E5%85%89%E6%A0%85%E5%8C%96.md)、[计算量与延迟](../../02_%E6%A6%82%E5%BF%B5/%E8%AE%A1%E7%AE%97%E9%87%8F%E4%B8%8E%E5%BB%B6%E8%BF%9F.md)、[二维高斯](../../02_%E6%A6%82%E5%BF%B5/%E4%BA%8C%E7%BB%B4%E9%AB%98%E6%96%AF.md)。

## 关联论文与证据

[QuADA-GS](../08_QuADA-GS_2026/QuADA-GS.md)：同任务的高效高斯方法比较；QuADA-GS 相关工作引用它，不据此断言直接继承。 关系分类及原始来源见检索记录；教学顺序不等于文献引用链。

## 本地原始附件

- [此前归档的 arXiv 正文 PDF](../../PUBLICATION_SCOPE.md) · 附件 `I25NTBDT` · SHA-256 `9e6bd947cd25c52c52481a0aa4c45cc091cfedbdb094b0192e8f7a77377c9293`

SI 来源状态：`check_embedded_appendices_in_paper_pdf`。独立SI与正文内嵌SI可能重叠，不计为独立论文。 文件已通过 Zotero 插件及受支持附件接口导入并回读路径/哈希；没有运行作者训练或复现实验。

## 阅读完成自检

- [ ] 能用三句话解释输入、输出与主要变化。
- [ ] 能画出特征或高斯如何到输出像素的流程。
- [ ] 能找到主实验的骨干、数据、退化、倍率、色彩空间及裁边条件。
- [ ] 能解释一个消融实验，同时指出它不能证明什么。

返回 [论文索引](../%E8%AE%BA%E6%96%87%E7%B4%A2%E5%BC%95.md) · [从LIIF到前沿的学习路线](../../00_%E5%AF%BC%E8%88%AA/%E4%BB%8ELIIF%E5%88%B0%E5%89%8D%E6%B2%BF%E7%9A%84%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF.md)。
