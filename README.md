<div align="center">

# 🧪 Prompt Refinement Lab

一个系统化、可复用且经过实战优化的 **个人提示词 Skill 库**

![License](https://img.shields.io/github/license/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=blue)
![Stars](https://img.shields.io/github/stars/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=gold)
![Last Commit](https://img.shields.io/github/last-commit/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=green)
![Context](https://img.shields.io/badge/Context-Global_Citizen-orange?style=for-the-badge)

</div>

---

## 📖 设计理念

本仓库旨在解决 Prompt Engineering 在实际落地中的“精度”与“稳定性”问题。不同于宽泛的指令，这里的每一个 Skill 都是我基于特定高频场景（如托福备考、专业摄影、博弈沟通）深度打磨的产物。

### 核心原则
- **反“废话”架构**：剥离所有 AI 常见的客套话与模板化表述，追求极致的信息密度。
- **高主体性 (High Agency)**：所有角色均设定为“教练”或“咨询师”，强调以用户为决策中心，AI 仅提供深度辅助。
- **工程化 SOP**：针对 A7M5 影像等复杂任务，将零散知识转化为可复现的标准化操作流程。

---

## 🚀 Skills 核心能力块

建议将选中的 `.txt` 内容直接作为 AI 模型的 **System Prompt**（系统指令）使用。

| Skill 模块 | 核心文件 | 适用场景与技术特性 |
| :--- | :--- | :--- |
| **深度天赋挖掘机** | [`talent-excavator.txt`](./prompts/talent-excavator.txt) | **职业/潜能挖掘**。基于“能量审计”与苏格拉底对话，挖掘底层迁移能力并生成万字说明书。 |
| **全球化英语教练** | [`english-writing.txt`](./prompts/english-writing.txt) | **托福备考/留学生活**。专攻中式思维纠偏，平衡“学术规范”与“地道口语”的落地场景。 |
| **百科全书系统** | [`encyclopedic-system.txt`](./prompts/encyclopedic-system.txt) | **深度研究/跨学科分析**。强调知识的纵向深度与横向联结，构建系统化知识树。 |
| **A7M5 影像专家** | [`photography-workflow.txt`](./prompts/photography-workflow.txt) | **专业摄影/视频 SOP**。基于 S-Log3 暴露规范与 XDR 色彩管理，解决工程级后期问题。 |
| **高主体性关系策略** | [`relationship-analyst.txt`](./prompts/relationship-analyst.txt) | **核心博弈/边界建立**。引入进化心理学视角，通过信号解码与高位重构，找回关系掌控权。 |

---

## 📁 库结构说明

```text
prompt-refinement-lab/
├── prompts/                   # 经优化后的 Skill 集合
│   ├── talent-excavator.txt   # 天赋挖掘（源自：数字生命卡兹克）
│   ├── english-writing.txt    # 托福/出国实战英语
│   ├── encyclopedic-system.txt# 跨学科百科全书
│   ├── photography-workflow.txt# 摄影/视频全流程 SOP
│   └── relationship-analyst.txt# 关系博弈策略
├── README.md
└── LICENSE
```

---

## 🛠️ 执行建议

为了获得最大化的输出效能，推荐遵循以下工程建议：

1. **单点注入**：每次对话仅注入一个 Skill，避免模型因角色重叠导致逻辑退化。
2. **环境适配**：
   - **ChatGPT / Claude**: 建议配置在 Custom Instructions 或 Project Knowledge 中。
   - **Cursor**: 可直接作为 `.cursorrules` 的引用或参考。
3. **反馈闭环**：
   - 特别是“天赋挖掘机”等交互型提示词，需严格遵守其“One Question at a Time”的节奏，以保证信息提取的深度。
   - 随时通过“提供具体场景”或“切换表达语域”来微调输出精度。

---

## 📜 声明

这里的每一行提示词都是为了减少重复劳动。我将在这个仓库中持续更新经过我验证有效的 Skills。

本项目采用 [MIT License](./LICENSE) 协议。