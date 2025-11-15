<div align="center">
  <h1 align="center">🚀 Claude-Skills</h1>

  <p align="center">
    <strong>探索并分享高质量的Claude Code Agent Skills</strong>
    <br />
    <br />
    <a href="#快速开始">快速开始</a>
    ·
    <a href="#skill目录">浏览技能</a>
    ·
    <a href="#贡献指南">贡献技能</a>
  </p>
</div>

---

## 🎯 核心价值

Claude-Skills是一个**技能分享仓库**，汇集了精心设计的Claude Code Agent Skills，让你的Claude变得更加强大和专业化。

**三大优势：**
- ✅ **即插即用**：每个技能都是独立模块，复制即可使用
- ✅  **️案例驱动**  ：每个技能都包含详细的示例和最佳实践
- ✅ **社区共建**：开源协作，持续优化

---

## 📦 Skill目录

| 名称 | 核心价值 | 适用场景 |
| :--- | :--- | :--- |
| **super-analyst** 🔍 | 专业级分析和研究能力，集成深度思考和网络搜索 | 市场分析、竞品研究、商业决策 |
| **super-writer** ✍️ | 专业内容创作助手，支持风格分析和多种写作方法论 | 撰写博客、营销文案、技术文档 |
| **skill-creator** 🛠️ | 交互式创建Claude Skills，自动生成标准文档 | 开发新技能、技能迭代 |
| **codex** 💻 | OpenAI Codex CLI集成，自动化代码编辑和重构 | 代码分析、自动化重构 |
| **artifacts-builder** 🎨 | 使用React+Tailwind构建复杂claude.ai HTML工件 | 创建交互式数据可视化组件 |
| **pdf** 📄 | PDF文档综合处理工具包（提取文本、表单、创建新文档） | 批次处理PDF、表单填写 |
| **pptx** 📊 | PowerPoint创建、编辑和分析（支持OOXML和HTML转PPT） | 自动生成演示文稿 |
| **docx** 📝 | Word文档创建、编辑和文本提取（支持OOXML） | 合同生成、文档处理 |
| **xlsx** 📈 | 电子表格创建、公式计算、数据分析和可视化 | 财务报表、数据处理 |

---

## 🚀 快速开始

### 步骤1：安装

```bash
git clone https://github.com/yourusername/claude-skills.git ~/.claude/skills/
cd ~/.claude/skills/
```

### 步骤2：配置Claude Code

Claude Code会自动加载 `~/.claude/skills/` 目录下的所有技能。

### 步骤3：开始体验

```bash
# 示例：使用super-analyst进行市场分析
# 在Claude Code中直接对话：
"用super-analyst帮我分析AI市场趋势"

# 示例：使用super-writer撰写内容
"用super-writer写一篇关于Claude Code的技术博客"
```

---

## 💡 使用场景

### 场景1：初创公司市场研究 🚀

**痛点**：需要快速了解竞品和市场机会
**方案**：
```bash
# 使用super-analyst进行综合分析
对话示例："分析我们的3个主要竞品，给出SWOT分析"

输出：自动网络搜索 + 结构化分析 + 可视化报告
```

### 场景2：技术团队内容营销 📣

**痛点**：缺乏专业的技术内容创作能力
**方案**：
```bash
# 使用super-writer撰写高质量文章
对话示例："基于我们的GitHub更新，写一篇技术博客"

输出：材料收集 + 风格分析 + 专业写作 = 高质量文章
```

### 场景3：自动化文档处理 📊

**痛点**：重复性文档处理工作耗时耗力
**方案**：
```bash
# 使用pdf/docx/pptx批量处理
对话示例："提取所有客户合同中的关键条款并生成汇总表"

输出：自动解析 + 数据提取 + Excel导出
```

---

## 🏗️ 项目结构

```
claude-skills/
├── .claude/
│   └── settings.local.json          # 配置示例
├── artifacts-builder/               # 前端工件构建
│   ├── SKILL.md
│   ├── LICENSE.txt
│   └── scripts/
├── codex/                          # OpenAI Codex集成
│   └── SKILL.md
├── docx/                           # Word文档处理
│   ├── SKILL.md
│   ├── docx-js.md
│   └── ooxml.md
├── pdf/                            # PDF表单处理
│   ├── SKILL.md
│   ├── REFERENCE.md
│   └── FORMS.md
├── pptx/                           # PowerPoint处理
│   ├── SKILL.md
│   ├── ooxml.md
│   └── html2pptx.md
├── skill-creator/                  # 技能创建助手
│   ├── SKILL.md
│   └── templates/
├── super-analyst/                  # 超级分析助手
│   ├── SKILL.md
│   ├── README.md
│   ├── CHANGELOG.md
│   └── references/
├── super-writer/                   # 专业写作助手
│   └── SKILL.md
└── xlsx/                           # 电子表格处理
    └── SKILL.md
```

---

## 🛠️ 技术栈

- **MCP框架**：Model Context Protocol Agent Skills
- **支持模型**：Claude 3.5 Sonnet, Claude 3 Opus
- **集成工具**：OpenAI Codex CLI, Prompt House
- **前端技术**：React 18, TypeScript, Tailwind CSS, shadcn/ui
- **文档处理**：PDF, OOXML, Office格式
- **开发环境**：Node.js 18+, Python 3.8+

---

## 🤝 贡献指南

欢迎贡献新技能或改进现有技能！

### 提交新技能

```bash
# 1. Fork仓库
# 2. 使用skill-creator创建技能：
在Claude Code中：
"用skill-creator创建新技能"

# 3. 遵循规范：
#    - 小写下划线命名（如：data_analyzer）
#    - 必须包含SKILL.md
#    - 推荐README.md使用说明

# 4. 测试并提交PR
```

**代码规范**：
- 保持统一风格
- 文档使用中文（描述性内容）
- 代码注释清晰
- 包含错误处理

**更多信息**：查看具体技能的README.md文件

---

## 🎯 路线图

- [ ] 添加CSV/JSON/XML处理技能
- [ ] 集成Gemini和GPT-4模型
- [ ] 开发可视化配置界面
- [ ] 构建社区技能市场
- [ ] 添加自动化测试套件
- [ ] 支持技能依赖管理

---

## 📝 版本历史

- **v1.0.0** (2025-01)：初始版本，包含9个核心技能

---

## 📄 许可证

[MIT License](LICENSE)

---

<div align="center">
  <sub>Built with ❤️ by the Claude Community</sub>
</div>
