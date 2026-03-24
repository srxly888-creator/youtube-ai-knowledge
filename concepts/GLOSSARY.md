# 📚 概念术语对照表

> 统一中英文术语，确保知识图谱一致性

---

## 🎯 术语规范

### 保留英文的专业名词

| 类别 | 英文术语 | 说明 |
|------|----------|------|
| **技术名词** | LLM, Token, AI, AGI, ASI | 业内公认术语 |
| **公司名称** | Anthropic, OpenAI, Google | 公司名 |
| **模型名称** | Gemini, Claude, GPT, ChatGPT | 模型名 |
| **技术架构** | Transformer, RAG, Function Calling | 核心技术 |
| **工具名称** | Notebook LM, memU, Cursor | 工具名 |

### 中英文对照

| 中文术语 | 英文术语 | 缩写/别名 | 说明 |
|----------|----------|-----------|------|
| 大语言模型 | Large Language Model | LLM | 核心概念 |
| 提示词工程 | Prompt Engineering | - | AI 应用 |
| 检索增强生成 | Retrieval-Augmented Generation | RAG | 技术架构 |
| 函数调用 | Function Calling | - | Agent 能力 |
| 向量数据库 | Vector Database | Vector DB | 存储技术 |
| 知识图谱 | Knowledge Graph | KG | 结构化知识 |
| 思维链 | Chain of Thought | CoT | 推理技巧 |
| 思维树 | Tree of Thought | ToT | 推理技巧 |
| 微调 | Fine-tuning | - | 训练方法 |
| 嵌入 | Embedding | - | 向量化 |
| 代理 | Agent | - | 智能系统 |
| 工作流 | Workflow | - | 任务流程 |
| 软件即服务 | Software as a Service | SaaS | 商业模式 |
| 金融科技 | Financial Technology | FinTech | 行业应用 |

---

## 📖 概念文件命名规范

### 规则
1. **核心概念**: 中文优先，英文标注
   - 示例: `LLM-Overview.md` → `大语言模型-详解.md`
   - 格式: `[[中文概念名]]` → 双链

2. **专业术语**: 保留英文，添加中文说明
   - 示例: `[[RAG]]` → `[[RAG-检索增强生成]]`
   - 格式: `[[英文术语-中文说明]]`

3. **混合命名**: 中英文结合
   - 示例: `AI-Agent.md` → `AI-代理.md`
   - 格式: `英文-中文.md`

---

## 🔄 文件重命名计划

### 核心概念（中文优先）

| 原文件名 | 新文件名 | 双链格式 |
|----------|----------|----------|
| LLM-Overview.md | 大语言模型-详解.md | [[大语言模型]] |
| AI-Agent.md | AI-代理.md | [[AI 代理]] |
| Prompt-Engineering.md | 提示词工程.md | [[提示词工程]] |
| RAG.md | RAG-检索增强生成.md | [[RAG]] |
| AI-Coding.md | AI-编程.md | [[AI 编程]] |
| Function-Calling.md | 函数调用.md | [[函数调用]] |
| Notebook-LM.md | Notebook-LM-详解.md | [[Notebook LM]] |
| memU-Memory-System.md | memU-记忆系统.md | [[memU 记忆系统]] |
| One-Person-AI-Company.md | 一人AI公司.md | [[一人 AI 公司]] |

### 索引文件（保持原名）

- README.md → README.md（不变）
- INDEX.md → INDEX.md（不变）
- knowledge-graph.md → knowledge-graph.md（不变）
- X-Bookmarks-Mapping.md → X-书签映射.md（可选）

---

## 💡 使用建议

### 在 Obsidian 中

1. **双链格式**:
   - 中文概念: `[[大语言模型]]`
   - 英文术语: `[[RAG]]` 或 `[[RAG-检索增强生成]]`

2. **别名设置**:
   ```markdown
   ---
   aliases: [LLM, Large Language Model]
   ---
   ```

3. **重定向**:
   创建英文文件，重定向到中文文件：
   ```markdown
   # LLM

   重定向到 [[大语言模型]]
   ```

---

## 🎯 执行优先级

### 🔴 P0 - 核心概念（立即执行）
1. 大语言模型
2. AI 代理
3. 提示词工程
4. RAG

### 🟡 P1 - 重要概念（本周完成）
5. AI 编程
6. 函数调用
7. Notebook LM
8. memU 记忆系统

### 🟢 P2 - 其他概念（本月完成）
9. 一人 AI 公司
10. 其他概念

---

**创建时间**: 2026-03-24
**状态**: ⏳ 待执行
**预计完成**: 2026-03-24 12:00
