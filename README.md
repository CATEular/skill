# Eularcat Skills

我的个人开发技能库，包含可阅读的技能指令、辅助脚本、模板与配置示例。
Personal agent skills for analog IC research and Virtuoso workflows.

## 技能 / Skills

| 技能 | 用途 |
| --- | --- |
| [Analog IC Notes](skills/analog-ic-notes/SKILL.md) | 模拟与混合信号 IC 论文精读、引用和配图整理、Markdown / Obsidian 笔记 |
| [Zotero Reading Notes](skills/zotero-reading-notes/SKILL.md) | 按个人颜色与笔记偏好，将单篇 Zotero 批注增量整理进 Obsidian |
| [virtuoso-connect](skills/virtuoso-workflow/virtuoso-connect/SKILL.md) | Python、bridge、SSH 与 CIW 连接检查和诊断 |
| [virtuoso-testbench](skills/virtuoso-workflow/virtuoso-testbench/SKILL.md) | 原理图、符号、测试平台、ADE 和单次仿真 |
| [virtuoso-params](skills/virtuoso-workflow/virtuoso-params/SKILL.md) | 基于测量反馈的参数调整、GP 建议与独立复测 |
| [virtuoso-layout](skills/virtuoso-workflow/virtuoso-layout/SKILL.md) | 版图和 DRC / LVS / PEX 流程 |
| [virtuoso-helper](skills/virtuoso-workflow/virtuoso-helper/SKILL.md) | Virtuoso 菜单、快捷键、概念和文档说明 |

## 获取与安装 / Install

克隆本仓库，或下载单套技能 ZIP：

```sh
git clone https://github.com/CATEular/skill.git
```

- [Analog IC Notes ZIP](downloads/analog-ic-notes.zip)：解压后将 analog-ic-notes 文件夹放入所用 Agent 支持的技能目录，按 [SKILL.md](skills/analog-ic-notes/SKILL.md) 配置自己的论文与笔记目录。
- [Zotero Reading Notes ZIP](downloads/zotero-reading-notes.zip)：解压后安装 `zotero-reading-notes` 文件夹。首次使用请 Agent 确认文库与笔记位置、各批注颜色含义、语言与详略，以及是否需要知识卡，保存为本地 `config.local.json`；已有偏好直接沿用。详见 [首次配置](skills/zotero-reading-notes/references/preferences.md)。颜色表仅是可选示例，不代表所有人的阅读习惯。
- [Virtuoso Workflow ZIP](downloads/virtuoso-workflow.zip)：按 [安装说明](skills/virtuoso-workflow/README.md) 安装；五个 virtuoso-* 文件夹必须保持同级，相对引用需要这一结构。

先审阅技能说明和脚本，再执行需要的操作。将配置示例复制为自己的 config.local.json；不要覆盖已有配置，也不要提交凭据、个人目录、PDK 或设计数据库。Virtuoso 操作需要自己的外部 bridge、Cadence 软件、许可和授权环境。

## 许可与来源 / License and attribution

原创内容以 [MIT License](LICENSE) 开源。第三方内容保留其原有版权和许可，参见 [来源说明](skills/virtuoso-workflow/ATTRIBUTION.md) 与 [bridge MIT 许可](skills/virtuoso-workflow/LICENSE.bridge)。本仓库不分发 Cadence 软件、PDK、论文 PDF 或私人项目。
