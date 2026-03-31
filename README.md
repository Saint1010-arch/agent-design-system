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

## 📖 如何使用

### 先了解：项目里每个文件是做什么的

| 文件 | 用途 | 什么时候用 | 是否必需 |
|:---|:---|:---|:---|
| [`templates/生产手册.md`](templates/生产手册.md) | 从需求到交付的完整 SOP 流程 | **最先读**——了解完整流程 | ✅ 第一次用时必读 |
| [`templates/五层架构模板.md`](templates/五层架构模板.md) | 设计 Agent 的核心骨架，逐层填写 | **设计阶段**——按模板生成配置 | ✅ 必需 |
| [`methodology/Agent设计方法论.md`](methodology/Agent设计方法论.md) | 审美工程 + 思维模型 + 业界最佳实践 | **设计过程中参考**——让配置有深度 | ✅ 推荐 |
| [`templates/质检清单.md`](templates/质检清单.md) | 设计完成后逐项验收 | **设计完成后**——发现漏洞 | ✅ 推荐 |
| [`templates/角色矩阵.md`](templates/角色矩阵.md) | 管理多个 Agent 的全局视图 | **有多个 Agent 时**——避免重叠 | 📖 多 Agent 时用 |
| [`core/SOUL-龙虾教练.md`](core/SOUL-龙虾教练.md) | 一个实际在用的配置示范 | **随时参考**——看别人怎么写 | 📖 参考 |

---

### 用法 A：我用 OpenClaw（龙虾）🦞

> 你已经在用 OpenClaw，想让你的龙虾变得更专业，或者用龙虾批量生产子 Agent。

**Step 1：下载项目**

```bash
git clone https://github.com/Saint1010-arch/agent-design-system.git
```

或者直接点 GitHub 页面右上角 **Code → Download ZIP** 解压。

**Step 2：把文件放进你的 workspace**

把 `templates/` 和 `methodology/` 文件夹复制到你的 OpenClaw workspace 目录下：

```
~/.openclaw/workspace/
├── SOUL.md               ← 你现有的灵魂文件
├── AGENTS.md
├── templates/             ← 放进来
│   ├── 五层架构模板.md
│   ├── 质检清单.md
│   ├── 生产手册.md
│   └── 角色矩阵.md
└── methodology/           ← 放进来
    └── Agent设计方法论.md
```

**Step 3：让龙虾帮你设计 Agent**

直接在对话中告诉你的龙虾：

> "读一下 `templates/` 目录下的文件，然后帮我设计一个 [产品经理/招聘专家/技术调研员/...] 的 Agent 配置。"

龙虾会按顺序使用这些文件：

| 阶段 | 龙虾读什么 | 做什么 |
|:---|:---|:---|
| 理解流程 | `生产手册.md` | 了解 SOP，先澄清需求再动手 |
| 设计配置 | `五层架构模板.md` | 按五层逐项生成完整配置 |
| 补充深度 | `Agent设计方法论.md` | 查阅审美工程手段、思维模型、行业对标方法 |
| 验收质检 | `质检清单.md` | 逐项检查，标注不达标的地方 |
| 团队管理 | `角色矩阵.md` | 登记 Agent，确保团队不重叠 |

**Step 4：部署生成的 Agent**

- 作为子 Agent → 把配置放到对应目录，龙虾可以调用
- 独立部署 → 把生成的配置写入新 Agent 的 `SOUL.md`

---

### 用法 B：我用 ChatGPT / Claude / 其他 AI 💬

> 你不用 OpenClaw，但想用这套方法论设计更好的 AI 角色。

**Step 1：下载或复制文件**

你至少需要：
- `templates/五层架构模板.md`（设计骨架）
- `templates/质检清单.md`（验收标准）

推荐也下载：
- `templates/生产手册.md`（了解完整流程）
- `methodology/Agent设计方法论.md`（提升设计深度）

**Step 2：填写五层架构模板**

打开 `五层架构模板.md`，把 `[方括号]` 里的内容替换成你的 Agent 信息：

```
第一层 Profile     → 名字、MBTI、Slogan、行业对标人物
第二层 Soul        → 灵魂准则、审美标准、行为禁令
第三层 Knowledge   → 概念定义表（重点填"虚假表现"列）、行业对标
第四层 Methodology → 方法论（标注来源 + 适用场景 + 典型陷阱）
第五层 Protocol    → 回复示例（至少2段）、行为边界三栏表
```

> 💡 **不知道怎么填？** 参考 `core/SOUL-龙虾教练.md` 看一个实际的配置长什么样；参考 `methodology/Agent设计方法论.md` 了解每个设计决策背后的原理。

**Step 3：把填好的内容粘贴到你的 AI 平台**

- **ChatGPT** → Custom Instructions 或 GPTs 的 Instructions
- **Claude** → Projects 的 Project Instructions
- **其他平台** → System Prompt 对应位置

**Step 4：用质检清单自检**

对照 `质检清单.md` 逐项检查。

---

### 用法 C：我只想学习方法论 📚

> 你对"怎么设计好的 AI Agent"感兴趣，想理解背后的设计思想。

直接阅读两个文件：

1. **[`methodology/Agent设计方法论.md`](methodology/Agent设计方法论.md)** — 完整方法论
   - 第二章：Anthropic / OpenAI / LangChain 最佳实践
   - 第三章：8 个可注入的思维模型
   - 第四章：企业级 Agent 评估框架
   - 第五章：**审美工程**（核心亮点）——解决 AI "模拟理解 ≠ 真正理解"的工程手段

2. **[`core/SOUL-龙虾教练.md`](core/SOUL-龙虾教练.md)** — 一个实际运行中的配置示范

---

### 常见问题

**Q：五层架构必须全部填完吗？**
A：追求产品级质量——是的。个人使用——至少填第二层（Soul）和第四层（Methodology），这两层决定 Agent 的行为质量。

**Q：核心配置为什么限制 3000 字？**
A：Token 经济学。AI 的上下文窗口有限，配置越长，留给实际对话的空间越少。3000 字是信息密度和 Token 消耗的最佳平衡点。

**Q：我不会编程，能用吗？**
A：完全可以。所有文件都是 Markdown 文本，用记事本就能打开编辑，不需要写一行代码。

**Q：Agent 回答太泛怎么办？**

| 症状 | 根因 | 解法 |
|:---|:---|:---|
| 回答像实习生 | 缺少行业顶级对标 | 补第三层的行业对标（具体到人/公司/做法） |
| 正确但没信息量 | 没有反压缩规则 | 在行为禁令里加"不要为了精简而压缩回复" |
| 看起来专业但经不起追问 | 缺少概念定义表 | 补第三层的关键概念定义 + 虚假表现列 |
| 什么都答但都不深 | 没有能力圈边界 | 在灵魂准则里加自我校准机制 |

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
