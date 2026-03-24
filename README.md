# 📺 YouTube AI 知识字幕库

> 收录 393 个 AI 相关视频字幕，涵盖人工智能、机器学习、深度学习、LLM 等主题

## 📊 统计信息

- **字幕总数**: 393 个
- **文件大小**: 339MB
- **更新时间**: 2026-03-24
- **来源频道**:
  - Diary of a CEO (346 个字幕)
  - Best Partners (39 个字幕)
  - Wow Insight (14 个字幕)

## 🎯 内容分类

### 人工智能基础
- 机器学习入门
- 深度学习原理
- 神经网络架构

### LLM 专题
- GPT 系列模型
- Claude 使用技巧
- Prompt Engineering

### AI 应用
- AI 编程助手
- 自动化工具
- AI 产品设计

### 前沿趋势
- AI 安全与伦理
- AGI 研究
- 行业应用案例

## 📁 文件结构

```
youtube-ai-knowledge/
├── bestpartners-subtitles/      # Best Partners 频道（39 个）
├── diaryofaceo-subtitles/       # Diary of a CEO 频道（346 个）
├── wowinsight-subtitles/        # Wow Insight 频道（14 个）
├── concepts/                    # 核心概念图谱（25 个核心概念）
│   ├── INDEX.md                 # 概念索引
│   ├── knowledge-graph.md       # 知识图谱可视化
│   └── *.md                     # 各概念详细说明
└── KNOWLEDGE-GRAPH-REPORT.md    # 知识图谱分析报告
```

## 🔍 使用方法

### 1. 克隆仓库
```bash
git clone https://github.com/srxly888-creator/youtube-ai-knowledge.git
cd youtube-ai-knowledge
```

### 2. 搜索字幕
```bash
# 搜索关键词
grep -r "人工智能" . --include="*.vtt"

# 统计字幕数量
find . -name "*.vtt" | wc -l
```

### 3. 转换为学习笔记
```bash
# 使用 AI 工具总结字幕
python scripts/vtt_to_notes.py
```

## 🧠 知识图谱与双链系统

### 核心概念（25 个）

| 类别 | 概念 | 说明 |
|------|------|------|
| **大语言模型** | [[GLM-5]], [[Claude Opus 4.6]], [[ChatGPT]], [[GPT-4]], [[DeepSeek]], [[X-AI-Grok]] | 核心生成引擎 |
| **AI 应用** | [[AI 代理]], [[AI 编程]], [[提示词工程]], [[RAG-检索增强生成]] | 实际应用场景 |
| **技术架构** | [[Transformer]], [[微调]], [[向量数据库]], [[知识图谱]] | 底层技术 |
| **核心能力** | [[函数调用]], [[任务规划]], [[自我反思]] | Agent 能力 |
| **行业应用** | [[SaaS]], [[金融科技]], [[企业管理]], [[自动化工作流]] | 商业应用 |
| **社会影响** | [[AI 与就业]], [[AI 伦理]], [[AI 安全]], [[AGI]] | 社会层面 |
| **X 书签新增** | [[Notebook LM]], [[memU 记忆系统]], [[一人 AI 公司]] | 高价值内容 |

### 知识图谱
- **可视化图谱**: `concepts/knowledge-graph.md`（Mermaid 格式）
- **概念索引**: `concepts/INDEX.md`（字幕与概念映射）
- **双链导航**: 使用 Obsidian 打开查看关联关系

### 使用方法
1. **克隆仓库** → 用 Obsidian 打开
2. **查看图谱** → 使用 Graph View 可视化
3. **双链导航** → 点击 [[概念名]] 跳转
4. **字幕溯源** → 每个概念关联原始字幕

---

## 🎓 学习路径

### 入门级（0-3 个月）
1. **AI 基础概念** - [[大语言模型]], [[Transformer]]
2. **机器学习入门** - 监督/无监督学习
3. **Python 编程** - 基础语法 + 实践

### 进阶级（3-6 个月）
1. **深度学习框架** - PyTorch/TensorFlow
2. **NLP 基础** - 文本处理 + 向量化
3. **Prompt Engineering** - 提示词设计技巧

### 高级（6-12 个月）
1. **模型微调** - LoRA/QLoRA
2. **RAG 应用** - 检索增强生成
3. **Agent 开发** - Function Calling + 多智能体

## 📚 相关仓库

- [youtube-vibe-coding](https://github.com/srxly888-creator/youtube-vibe-coding) - AI 编程技巧
- [youtube-health-wellness](https://github.com/srxly888-creator/youtube-health-wellness) - 健康养生
- [youtube-life-entertainment](https://github.com/srxly888-creator/youtube-life-entertainment) - 生活娱乐

## 📜 许可证

本仓库仅供学习研究使用，字幕版权归原作者所有。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

⭐ 如果这个仓库对你有帮助，请给一个 Star！
者所有。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

⭐ 如果这个仓库对你有帮助，请给一个 Star！
