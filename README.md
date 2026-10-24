# Eularcat Skills

我的个人开发技能库，包含可阅读的技能指令、辅助脚本、模板与配置示例。
Personal agent skills for analog IC research and Virtuoso workflows.

## 技能 / Skills

| 技能 | 用途 |
| --- | --- |
| [Analog IC Notes](skills/analog-ic-notes/SKILL.md) | 模拟与混合信号 IC 论文精读、引用和配图整理、Markdown / Obsidian 笔记 |
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
- [Virtuoso Workflow ZIP](downloads/virtuoso-workflow.zip)：按 [安装说明](skills/virtuoso-workflow/README.md) 安装；五个 virtuoso-* 文件夹必须保持同级，相对引用需要这一结构。

先审阅技能说明和脚本，再执行需要的操作。将配置示例复制为自己的 config.local.json；不要覆盖已有配置，也不要提交凭据、个人目录、PDK 或设计数据库。Virtuoso 操作需要自己的外部 bridge、Cadence 软件、许可和授权环境。

## 许可与来源 / License and attribution

原创内容以 [MIT License](LICENSE) 开源。第三方内容保留其原有版权和许可，参见 [来源说明](skills/virtuoso-workflow/ATTRIBUTION.md) 与 [bridge MIT 许可](skills/virtuoso-workflow/LICENSE.bridge)。本仓库不分发 Cadence 软件、PDK、论文 PDF 或私人项目。
