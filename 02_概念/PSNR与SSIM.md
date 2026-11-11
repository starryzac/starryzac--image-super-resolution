---
type: concept
aliases:
  - "PSNR"
  - "SSIM"
  - "evaluation protocol"
status: 原创入门解释
updated: 2026-10-29
tags: [概念, 图像超分辨率]
---

# PSNR与SSIM

PSNR=10 log10(L²/MSE)，L是像素动态范围上限；MSE越小，PSNR越高。SSIM比较局部亮度、对比度和结构相似性。两者都需要相应参考图，且受色彩空间、裁边、缩放实现影响。

## 一个小例子

归一化像素L=1，MSE=0.01时PSNR=20dB；MSE减半提高约3.01dB。RGB结果不能直接和只算Y通道的结果排高低。

## 在路线中的位置

相关论文：[LIIF](../01_%E8%AE%BA%E6%96%87/01_LIIF_2021/LIIF.md)、[LTE](../01_%E8%AE%BA%E6%96%87/02_LTE_2022/LTE.md)、[CiaoSR](../01_%E8%AE%BA%E6%96%87/03_CiaoSR_2023/CiaoSR.md)、[SRNO](../01_%E8%AE%BA%E6%96%87/04_SRNO_2023/SRNO.md)、[GaussianSR](../01_%E8%AE%BA%E6%96%87/05_GaussianSR_2025/GaussianSR.md)、[GSASR](../01_%E8%AE%BA%E6%96%87/06_GSASR_2025/GSASR.md)、[ContinuousSR](../01_%E8%AE%BA%E6%96%87/07_ContinuousSR_2026/ContinuousSR.md)、[QuADA-GS](../01_%E8%AE%BA%E6%96%87/08_QuADA-GS_2026/QuADA-GS.md)。这些链接表示阅读时会用到此概念，除论文卡明确注明外不代表论文之间直接继承。

先后联系：[损失函数](%E6%8D%9F%E5%A4%B1%E5%87%BD%E6%95%B0.md)、[保真与感知质量](%E4%BF%9D%E7%9C%9F%E4%B8%8E%E6%84%9F%E7%9F%A5%E8%B4%A8%E9%87%8F.md)。

本页是学习者用的原创解释；论文中的精确定义、边界与实验条件以各论文正文及源页映射为准。学习入口：[从LIIF开始的零基础学习手册](../04_%E6%95%99%E5%AD%A6/%E4%BB%8ELIIF%E5%BC%80%E5%A7%8B%E7%9A%84%E9%9B%B6%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0%E6%89%8B%E5%86%8C.md)。
