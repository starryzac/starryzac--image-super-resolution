---
title: 整理后的目录与PDF位置
date: 2026-11-06
tags: [导航, 目录管理, PDF]
---

# 整理后的目录与PDF位置

自2026-11-06起，除科研skills外，图像超分辨率相关资料统一放在 `LOCAL_VAULT`。

| 目录或入口 | 内容 |
|---|---|
| `PDF原文` | 便于直接阅读的12份PDF副本（2份重复SI已由完整稿覆盖），直接平铺PDF文件，用文件名区分论文、正文版本与补充材料 |
| `Zotero/data/storage` | Zotero管理的归档原附件，保留原附件key与文件名 |
| `Zotero/profile` | 项目独立配置；端口23279 |
| `Zotero/inbox`、`Zotero/exports` | 下载/待处理原文件与文献导出；是否入库以条目和附件回读为准 |
| `00_导航`至`06_附件` | 原有论文卡片、概念、教学、实验与图像附件 |
| `90_项目管理` | 项目规则、交接、验收说明与来源许可证 |
| `tools`、`evidence` | 操作脚本与验收证据 |
| `.runtime`、`.cache`、`cache` | 项目依赖与缓存 |
| `ObsidianApp`、`.obsidian` | 项目应用配置与仓库配置 |
| `打开项目Zotero.ps1`、`Zotero（图像超分辨率）.lnk` | 从新目录启动独立Zotero |
| `打开Obsidian仓库.ps1`、`Obsidian（图像超分辨率）.lnk` | 打开本仓库 |

科研skills实际放在外层 `LOCAL_VAULT\科研skills`，外层 `.agents/skills` 是指向它的发现入口。外层 `AGENTS.md` 与本仓库规则文件仍为硬链接。

## 直接打开原文

[点击查看全部PDF原文副本](PDF%E5%8E%9F%E6%96%87%E7%B4%A2%E5%BC%95.md)。8篇论文、14份附件、7篇完整中英对照是三个不同数量。ContinuousSR目前只有2025年arXiv v1原文及中文导读，未取得2026最终会议稿。

版本比较及取舍见[PDF版本比较与保留说明](../PUBLICATION_SCOPE.md)。以后PDF仍先在项目Zotero归档，再在当前目录执行 `python -B -X utf8 tools/sync_pdf_copies.py`。副本不替代入库，不代表新增论文。手动批注请另存文件，避免把批注版当作与归档原件相同的副本。

2026-11-06整理前修改过的文本已保存在 `evidence/reorganization-20261106/before-path-updates.zip`；路径迁移记录见同目录 `path-migration.json`。这些是路径迁移证据，不是新的全文审校或实验复现。

[返回研究入口](%E5%9B%BE%E5%83%8F%E8%B6%85%E5%88%86%E8%BE%A8%E7%8E%87%E7%A0%94%E7%A9%B6%E5%85%A5%E5%8F%A3.md) · [论文索引](../01_%E8%AE%BA%E6%96%87/%E8%AE%BA%E6%96%87%E7%B4%A2%E5%BC%95.md)。
