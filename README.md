<div align="center">

# 🧪 Prompt Refinement Lab

一个系统化、可复用且经过实战优化的 **个人 AI 能力（Skills & Prompts）库**

![License](https://img.shields.io/github/license/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=blue)
![Stars](https://img.shields.io/github/stars/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=gold)
![Last Commit](https://img.shields.io/github/last-commit/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=green)
![Context](https://img.shields.io/badge/Context-Global_Citizen-orange?style=for-the-badge)

</div>

---

## 📖 设计理念

本仓库旨在通过双轨制（Dual-Track）满足不同的 AI 交互需求：

1.  **Prompts (一次性调用)**：适用于 ChatGPT/Claude 网页端，即插即用，单点爆发力强。
2.  **Skills (Agentic 系统调用)**：适用于 Claude Code, Cursor 或定制化 Agent，具备结构化的 YAML 定义，方便系统自动化检索与调用。

---

## ⚡️ Prompts (即插即用版)

建议直接复制 `prompts/` 目录下的 `.txt` 内容。

| Prompt 模块 | 核心逻辑 | 适用场景 |
| :--- | :--- | :--- |
| **全能英语教练** | 地道表达与学术规范 | 刷托福、改邮件、课业辅导 |
| **深度天赋挖掘** | 能量审计对话流 | 个人潜力分析、职业导向 |
| **影像工程专家** | S-Log3 与色彩管理 | A7M5 拍摄及后期流程 |
| **关系博弈策略** | 高主体性与理性沟通 | 关系内耗解决、边界设定 |
| **百科全书系统** | 跨学科深度联结 | 系统化课题研究、学术深挖 |

---

## 🛠️ Skills (Agentic 专业版)

位于 `skills/` 目录下，每个 Skill 包含独立的 `SKILL.md` 定义，专为 **Claude Code**, **Cursor** 或 **Agentic Tools** 优化。

```text
skills/
├── talent-excavator/      # 深度天赋挖掘模块
├── english-writing/       # 全球英语教练模块
├── encyclopedic-system/   # 跨学科百科系统
├── photography-workflow/  # 摄影/视频 SOP 模块
└── relationship-analyst/  # 关系博弈策略模块
```

### 为什么使用 Skills 模式？
- **YAML 描述**：包含名称、描述和触发条件 (`when_to_use`)，方便 Agent 自主决策。
- **结构化输出**：强制执行特定的回答骨架，确保 AI 表现稳定。

---

## 📁 库结构

```text
prompt-refinement-lab/
├── prompts/                   # 用于手动复制的 .txt 指令
├── skills/                    # 用于 Agent 调用的结构化模块
│   └── [skill-name]/
│       └── SKILL.md           # Skill 定义文件
├── README.md
└── LICENSE
```

---

## 🚀 执行建议

- **网页端用户**：直接进入 `prompts/` 文件夹复制内容。
- **Claude Code / Agent 用户**：将本仓库路径添加到你的 Agent 知识库或 Skills 路径中。
- **核心约束**：提倡“One Question at a Time”，让 AI 与你深度互动，而非一次性产出废话。

---

## 📜 声明

这里的每一行指令都是为了减少重复劳动。我将在这个仓库中持续更新经过我验证有效的原子级能力。

本项目采用 [MIT License](./LICENSE) 协议。