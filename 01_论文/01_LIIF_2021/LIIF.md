---
type: paper
aliases: ["LIIF", "Learning Continuous Image Representation with Local Implicit Image Function"]
arxiv: 2012.09161v2
year: 2021
venue: "CVPR 2021"
doi: "10.1109/CVPR46437.2021.00852"
source_pdf: "../../Zotero/data/storage/WMX9SPH6/Chen 等 - 2021 - Learning Continuous Image Representation with Local Implicit Image Function.pdf"
zotero_attachment_key: WMX9SPH6
source_basis: 用户提供会议版正文
zotero_key: Y68HLD8R
collection: LV8XCQ9B
source_checked: 2026-10-29
delivery: 用户提供会议版正文逐段中英对照；验收见交付记录
tags: [论文, 图像超分辨率]
---

# LIIF

**Learning Continuous Image Representation with Local Implicit Image Function**

作者：Yinbo Chen, Sifei Liu, Xiaolong Wang。发表信息：CVPR 2021。

出版物DOI：10.1109/CVPR46437.2021.00852。

[此前归档的 arXiv 版本](https://arxiv.org/abs/2012.09161v2) · 在Zotero中选择（溯源地址：`zotero://select/library/items/Y68HLD8R`） · [完整检索与版本记录](../../PUBLICATION_SCOPE.md)。

本轮对照以用户直接提供的 CVPR 会议版 PDF 为准，保留原权利信息；转换依据是用户提供文本，不将该版本标作 CC BY。此前归档的 arXiv 版本仍保留，用于版本核对。

## 先带着一个问题读

**连续坐标为什么能让一个模型输出不同大小的图像？**

本轮会议PDF第3–4页介绍局部潜码、邻域展开、局部集成和单元解码；共享解码器结合图像特征与查询位置给出颜色。第5–8页用于查看实验、消融与结论，第9–11页为书目。连续查询能力不保证无限真实细节。

学习内容：[逐段中英对照](../../PUBLICATION_SCOPE.md)。制作状态与覆盖边界见该文件和同目录 translation_notes；索引生成不代表全文已经验收。

相关概念：[隐式神经表示](../../02_%E6%A6%82%E5%BF%B5/%E9%9A%90%E5%BC%8F%E7%A5%9E%E7%BB%8F%E8%A1%A8%E7%A4%BA.md)、[局部集成](../../02_%E6%A6%82%E5%BF%B5/%E5%B1%80%E9%83%A8%E9%9B%86%E6%88%90.md)、[连续坐标与单元](../../02_%E6%A6%82%E5%BF%B5/%E8%BF%9E%E7%BB%AD%E5%9D%90%E6%A0%87%E4%B8%8E%E5%8D%95%E5%85%83.md)、[多层感知机](../../02_%E6%A6%82%E5%BF%B5/%E5%A4%9A%E5%B1%82%E6%84%9F%E7%9F%A5%E6%9C%BA.md)。

## 关联论文与证据

[LTE](../02_LTE_2022/LTE.md)：局部频率建模改进；LTE 引言与官方代码说明建立在 LIIF 基础上。 关系分类及原始来源见检索记录；教学顺序不等于文献引用链。

## 本地原始附件

- [此前归档的 arXiv 正文 PDF](../../PUBLICATION_SCOPE.md) · 附件 `XF6L4DE7` · SHA-256 `0157db20a4ca05c0f1b02ddf112315e41f1c5c0c20fd8b93f45860be92d0131d`
- [用户提供的会议版正文 PDF（本轮对照来源）](../../PUBLICATION_SCOPE.md) · 附件 `WMX9SPH6` · SHA-256 `ca53e19c3186a4a028bcff61243d4c79740b8b30d9eb6241664cd03275fada2f`

SI 来源状态：`not_found_on_official_pages`。本轮使用11页会议版正文，未取得独立SI。 文件已通过 Zotero 插件及受支持附件接口导入并回读路径/哈希；没有运行作者训练或复现实验。

## 阅读完成自检

- [ ] 能用三句话解释输入、输出与主要变化。
- [ ] 能画出特征或高斯如何到输出像素的流程。
- [ ] 能找到主实验的骨干、数据、退化、倍率、色彩空间及裁边条件。
- [ ] 能解释一个消融实验，同时指出它不能证明什么。

返回 [论文索引](../%E8%AE%BA%E6%96%87%E7%B4%A2%E5%BC%95.md) · [从LIIF到前沿的学习路线](../../00_%E5%AF%BC%E8%88%AA/%E4%BB%8ELIIF%E5%88%B0%E5%89%8D%E6%B2%BF%E7%9A%84%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF.md)。
