---
type: paper
aliases: ["CiaoSR", "CiaoSR: Continuous Implicit Attention-in-Attention Network for Arbitrary-Scale Image Super-Resolution"]
arxiv: 2212.04362v3
year: 2023
venue: "CVPR 2023"
doi: "10.1109/CVPR52729.2023.00179"
source_pdf: "../../Zotero/data/storage/ZH6V8CMK/Cao 等 - 2023 - CiaoSR Continuous Implicit Attention-in-Attention Network for Arbitrary-Scale Image Super-Resolutio.pdf"
zotero_attachment_key: ZH6V8CMK
source_basis: 用户提供会议版正文
zotero_key: 3QHEMV6Y
collection: LV8XCQ9B
source_checked: 2026-10-29
delivery: 用户提供会议版正文逐段中英对照；验收见交付记录
tags: [论文, 图像超分辨率]
---

# CiaoSR

**CiaoSR: Continuous Implicit Attention-in-Attention Network for Arbitrary-Scale Image Super-Resolution**

作者：Jiezhang Cao, Qin Wang, Yongqin Xian, Yawei Li, Bingbing Ni, Zhiming Pi, Kai Zhang, Yulun Zhang, Radu Timofte, Luc Van Gool。发表信息：CVPR 2023。

出版物DOI：10.1109/CVPR52729.2023.00179。

[此前归档的 arXiv 版本](https://arxiv.org/abs/2212.04362v3) · 在Zotero中选择（溯源地址：`zotero://select/library/items/3QHEMV6Y`） · [完整检索与版本记录](../../PUBLICATION_SCOPE.md)。

本轮对照以用户直接提供的 CVPR 会议版 PDF 为准，保留原权利信息；转换依据是用户提供文本，不将该版本标作 CC BY。此前归档的 arXiv 版本仍保留，用于版本核对。

## 先带着一个问题读

**邻域融合的权重能否由内容决定？**

会议PDF第1–2页说明内容相关聚合动机，第3–4页阅读方法与网络，第5–8页阅读实验；独立SI另存。它讨论局部集成的几何权重局限，引入连续隐式注意力以及非局部尺度感知信息。

学习内容：[逐段中英对照](../../PUBLICATION_SCOPE.md)。制作状态与覆盖边界见该文件和同目录 translation_notes；索引生成不代表全文已经验收。

相关概念：[注意力](../../02_%E6%A6%82%E5%BF%B5/%E6%B3%A8%E6%84%8F%E5%8A%9B.md)、[局部集成](../../02_%E6%A6%82%E5%BF%B5/%E5%B1%80%E9%83%A8%E9%9B%86%E6%88%90.md)、[张量与特征图](../../02_%E6%A6%82%E5%BF%B5/%E5%BC%A0%E9%87%8F%E4%B8%8E%E7%89%B9%E5%BE%81%E5%9B%BE.md)。

## 关联论文与证据

[SRNO](../04_SRNO_2023/SRNO.md)：同一任意倍率任务的另一分支；未断言 SRNO 直接继承 CiaoSR。 关系分类及原始来源见检索记录；教学顺序不等于文献引用链。

## 本地原始附件

- [补充 PDF](../../PUBLICATION_SCOPE.md) · 附件 `SLJ3EVNL` · SHA-256 `3ae2e1e3efbbcd0882ab84984f4f9e20ad1ebc1570b3af5e51aa09d7af3406ba`
- [此前归档的 arXiv 正文 PDF](../../PUBLICATION_SCOPE.md) · 附件 `BSKC2SNZ` · SHA-256 `021d3d43342760833d05f57dabf751c9a324035ad52f67910dff1f0eba5639ee`
- [用户提供的会议版正文 PDF（本轮对照来源）](../../PUBLICATION_SCOPE.md) · 附件 `ZH6V8CMK` · SHA-256 `4fd8c6d77ac1ef6bdc9214e7de3612576014642ac2abe2f77d9f57e4cd729c25`

SI 来源状态：`standalone_published_supplement_included`。本轮只翻译用户提供的会议版正文；原有独立 SI 已归档，尚未做逐段对照。 文件已通过 Zotero 插件及受支持附件接口导入并回读路径/哈希；没有运行作者训练或复现实验。

## 阅读完成自检

- [ ] 能用三句话解释输入、输出与主要变化。
- [ ] 能画出特征或高斯如何到输出像素的流程。
- [ ] 能找到主实验的骨干、数据、退化、倍率、色彩空间及裁边条件。
- [ ] 能解释一个消融实验，同时指出它不能证明什么。

返回 [论文索引](../%E8%AE%BA%E6%96%87%E7%B4%A2%E5%BC%95.md) · [从LIIF到前沿的学习路线](../../00_%E5%AF%BC%E8%88%AA/%E4%BB%8ELIIF%E5%88%B0%E5%89%8D%E6%B2%BF%E7%9A%84%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF.md)。
