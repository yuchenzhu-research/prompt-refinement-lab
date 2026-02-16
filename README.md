<div align="center">

# 🧪 Prompt Refinement Lab

一个系统化、可复用且经过实战优化的 **个人提示词 Skill 库**

![License](https://img.shields.io/github/license/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=blue)
![Stars](https://img.shields.io/github/stars/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=gold)
![Last Commit](https://img.shields.io/github/last-commit/yuchenzhu-research/prompt-refinement-lab?style=for-the-badge&color=green)
![Context](https://img.shields.io/badge/Context-Global_Citizen-orange?style=for-the-badge)

</div>

---

## 📖 碎碎念 (Why this matters)

这个仓库里的提示词，并不是那种“一句话搞定”的简单指令。

由于我正在准备托福并计划出国，同时也在深度折腾 A7M5 摄影，我发现市面上大部分提示词要么太虚（AI 味太重），要么太散（不符合工程逻辑）。所以我花了很多时间去“打磨”这套提示词：

- **从“实验室”到“生产工具”**：我已经把所有杂乱的测试过程和中间稿都删了，这里只留我每天都在用的最强版本。
- **实战导向**：比如英语教练，我不要那种教你“Hello”的，我要的是能帮我改出一封不卑不亢、专业得体的留美申请邮件，或者教我怎么在点餐时像个当地人。
- **高主体性**：所有的角色设定都强调**“我”才是控制者**。AI 是我的军师和教练，而不是那个替我做决定的人。

---

## 🚀 Skills (核心提示词库)

这里是我目前最核心的几个能力模块。建议直接把 `.txt` 里的内容贴到 AI 的 **System Prompt**（系统指令）里效果最好。

| Skill 名称 | 提示词文件 | 什么时候用它？ |
| :--- | :--- | :--- |
| **深度天赋挖掘机** | [`talent-excavator.txt`](./prompts/talent-excavator.txt) | **当你对未来迷茫时**。它会通过多轮对话掘你的“底层回血点”，而不是只看你技能。 |
| **全能英语教练** | [`english-writing.txt`](./prompts/english-writing.txt) | **备考托福或准备出国时**。专门对付中式思维，帮你改出地道、体面且符合学术规范的内容。 |
| **百科全书级系统** | [`encyclopedic-system.txt`](./prompts/encyclopedic-system.txt) | **需要深度研究课题时**。它能横向跨学科联想，纵向深挖历史脉络，拒绝废话回答。 |
| **A7M5 摄影专家** | [`photography-workflow.txt`](./prompts/photography-workflow.txt) | **用 A7M5 拍不出高级感时**。从曝光策略到后期 P3 色彩管理，提供一整套工程化操作。 |
| **高主体性关系顾问** | [`relationship-analyst.txt`](./prompts/relationship-analyst.txt) | **关系遇到内耗时**。基于博弈论和进化心理学，帮你识破信号，找回自己的掌控权。 |

---

## 📁 内部结构

```text
prompt-refinement-lab/
├── prompts/                   # 这是你可以直接拿来用的“子弹袋”
│   ├── talent-excavator.txt   # 天赋挖掘（万字说明书版）
│   ├── english-writing.txt    # 托福/出国实战英语
│   ├── encyclopedic-system.txt# 跨学科百科全书库
│   ├── photography-workflow.txt# 摄影/视频全流程 SOP
│   └── relationship-analyst.txt# 关系博弈策略
├── README.md
└── LICENSE
```

---

## � 怎么玩比较高效？

为了让这些提示词发挥最大威力，我建议你这么做：

1. **不要一键输入全部**：进入 `prompts/` 文件夹，选择一个你当下最需要的 `.txt`，一次只喂给 AI 一个角色。
2. **作为系统指令 (System Prompt)**：
   - 最好用在 ChatGPT Plus 的 "Custom Instructions"、Claude 的 "Projects" 或者 Cursor 的 `.cursorrules` 里。
3. **保持对话惯性**：
   - 特别是“天赋挖掘机”，它设定了“One Question at a Time”。**不要让它一次性列完问题**，你只需要回答它，剩下的交给它的节奏。
4. **针对性反问**：
   - 如果觉得它的回答还不够落地，可以直接说：“不够实战，再给点案例”，或者“换成更专业的英文语境”。

---

## 📜 碎碎念之二

代码和提示词都是死的，但思维是活的。我建立这个仓库是为了让自己少做重复劳动，多把心思花在真正的创造上。如果你有更好的优化思路，或者也在死磕地道翻译和专业影像，欢迎交流。

本项目采用 [MIT License](./LICENSE) 协议。