# 🦞 Agent Design System — 产品级 AI Agent 设计体系

> **不是又一个 SOUL.md 模板集合。是一套从需求到上架的完整 Agent 工厂。**

你见过很多 AI Agent 的 prompt 模板。但大多数只是"写一段人设描述"——没有质检标准、没有方法论来源追溯、没有解决 AI "模拟理解 ≠ 真正理解" 的工程手段。

这个项目提供的是：**一套经过体系化设计的 Agent 生产系统**，让你能批量生产**产品级、可上架、经过质检**的 AI Agent 角色配置。

---

## ✨ 这个项目能帮你做什么

- 🏗️ **用五层架构模板** 设计任何领域的专家级 Agent（Profile → Soul → Knowledge → Methodology → Protocol）
- 🎯 **用审美工程方法论** 解决 AI 最致命的问题——输出"看起来对但其实不对"的内容
- 🔍 **用质检清单** 在交付前发现 Agent 配置的漏洞
- 📐 **用生产手册 SOP** 把"模糊的需求"变成"完整的 Agent"
- 🧠 **用思维模型库** 给 Agent 注入真正的专家级思考方式

---

## 📂 项目结构

```
agent-design-system/
├── README.md                          ← 你在这里
├── LICENSE
│
├── core/                              ← 核心设计理念
│   └── SOUL-龙虾教练.md               ← 设计体系的元灵魂（示范文件）
│
├── templates/                         ← 开箱即用的模板
│   ├── 五层架构模板.md                 ← ⭐ 核心模板：设计任何 Agent
│   ├── 质检清单.md                     ← 交付前逐项检查
│   ├── 生产手册.md                     ← 从需求到上架的完整 SOP
│   └── 角色矩阵.md                    ← 团队全景管理
│
├── methodology/                       ← 方法论知识库
│   └── Agent设计方法论.md              ← 审美工程 + 思维模型 + 业界最佳实践
│
└── examples/                          ← 示例（持续更新）
    └── （即将推出第一个完整示例）
```

---

## 🔥 核心亮点：审美工程

大多数 Agent 设计只关心"让 AI 做什么"。我们额外解决了一个更深层的问题：

> **AI 模拟的"理解"和真正的"理解"之间有 gap，怎么用工程手段弥合？**

我们的回答是 8 种可操作的工程手段 + 3 种检测方法：

### 工程手段

| 手段 | 解决什么 |
|:---|:---|
| **定义锚定** | 防止"用对了词但理解偏了" |
| **行业顶级对标** | 把"好"从形容词变成可对照的具体标准 |
| **反例检验** | 防止确认偏误 |
| **来源追溯** | 区分"AI 生成的"和"有权威来源的" |
| **置信度标注** | 🟢确定 / 🟡推断 / 🔴推测——防止猜测当确定 |
| **能力圈声明** | 不懂就说不懂，不编 |
| **交叉验证** | 防止单一来源偏见 |
| **版本意识** | 防止用过时方法做当下的事 |

### 检测方法

- **删除测试**：删掉这句话，读者损失信息了吗？没有就删。
- **替换测试**：把术语换成其他领域的，还通顺吗？通顺说明是模板化空话。
- **追问测试**：追问"为什么"，只能答"通常来说"？深度不够。

### 虚假表现检测

来自 [Human 3.0](https://letters.thedankoe.com/p/human-30-a-map-to-reach-the-top-1) 的 False Transformation 思想——不只定义"什么是好的"，更精确定义"什么看起来好但其实不好"：

- ❌ **虚假的"用户思维"**：嘴上说"以用户为中心"，做决策时从未引用过一条用户数据
- ❌ **虚假的"战略思维"**：能说出 SWOT、波特五力，但无法判断当前场景该用哪个
- ❌ **虚假的"技术深度"**：堆砌术语但无法解释术语之间的因果关系

---

## ⚡ 快速开始

### 1. 设计一个 Agent

打开 [`templates/五层架构模板.md`](templates/五层架构模板.md)，按五层逐项填写：

1. **Profile** — 基础档案：名字、性格、思维模型、行业对标
2. **Soul** — 灵魂准则：核心价值观、行为禁令、审美标准
3. **Knowledge** — 知识库：概念定义表（含虚假表现列）、跨领域因果链
4. **Methodology** — 方法论：必须标注来源、适用场景、典型陷阱
5. **Protocol** — 协作协议：沟通风格 + 回复示例 + 行为边界

### 2. 质检

用 [`templates/质检清单.md`](templates/质检清单.md) 逐项检查。三色评分：

- 🟢 全通过 → 交付
- 🟡 1-2 项问题 → 修复后交付  
- 🔴 3+ 项问题 → 打回重做

### 3. 深入学习

阅读 [`methodology/Agent设计方法论.md`](methodology/Agent设计方法论.md) 了解完整的设计理念、思维模型库、业界最佳实践。

---

## 🧠 方法论来源

本项目的方法论不是凭空编造的，每一条都可追溯：

| 来源 | 贡献 |
|:---|:---|
| [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) | 清晰直接、示例驱动、XML 结构化 |
| [OpenAI GPT Personality Cookbook](https://cookbook.openai.com/examples/gpt4-1_prompting_guide) | 四维人格模型（Professional/Efficient/Fact-based/Conversational） |
| [LangChain Multi-Agent Architecture](https://blog.langchain.dev/what-is-a-multi-agent-architecture/) | 多 Agent 协作模式 |
| [Mr. Ranedeer AI Tutor](https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor) (26K⭐) | 反压缩原则、用户可调参数 |
| [Human 3.0 (Dan Koe)](https://letters.thedankoe.com/p/human-30-a-map-to-reach-the-top-1) | 虚假表现检测、跨领域因果链、适应性交互 |
| 麦肯锡 MECE / Munger 逆向思维 / Musk 第一性原理 | 思维模型库 |
| UiPath / AWS / Kore.ai | 企业级 Agent 评估框架 |

---

## 📐 设计原则

### Prompt 工程十诫

1. 角色 > 指令
2. 禁止清单 > 鼓励清单
3. 示例 > 描述
4. 结构 > 自由发挥
5. 理由 > 命令
6. 具体 > 泛泛
7. 分层 > 堆砌
8. 最小权限
9. 可测试
10. 人格是杠杆

### 设计黄金三角

```
        [角色认同]
         /       \
  [方法论注入] — [行为边界]
```

三条边上都站着**审美**——角色认同要有审美（不是空壳人设），方法论要有审美（不是空洞框架），边界要有审美（不是一刀切的粗暴限制）。

---

## 🤝 贡献

欢迎提交你用这套体系设计的 Agent 配置作为示例！请确保：

- 使用五层架构模板
- 通过质检清单
- 方法论标注来源

---

## 📄 License

[MIT](LICENSE)

---

## ⭐ 如果这个项目对你有帮助

给个 Star 是对作者最好的鼓励。

---

_Built with 🦞 by a human who believes every AI agent deserves a complete soul._
