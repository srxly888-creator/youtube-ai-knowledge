# AI Knowledge Graph - 内容分类整理方案

> **Issue**: #3 - 内容分类没有整理出文件夹吗
> **解决方案**: 重新组织目录结构

---

## 📂 新目录结构

```
ai-knowledge-graph/
├── README.md
├── KNOWLEDGE-GRAPH-REPORT.md
├── concepts/                    # 核心概念
│   └── *.md
├── subtitles/                   # 字幕分类
│   ├── bestpartners/           # 最佳拍档频道
│   ├── diaryofaceo/            # CEO 日记频道
│   └── wowinsight/             # WoW 洞察频道
└── scripts/                     # 处理脚本
    └── organize_content.sh
```

---

## 🔄 迁移计划

### 阶段 1: 创建新目录
```bash
mkdir -p subtitles/bestpartners
mkdir -p subtitles/diaryofaceo
mkdir -p subtitles/wowinsight
mkdir -p scripts
```

### 阶段 2: 移动文件
```bash
# 最佳拍档
mv bestpartners-subtitles/* subtitles/bestpartners/

# CEO 日记
mv diaryofaceo-subtitles/* subtitles/diaryofaceo/

# WoW 洞察
mv wowinsight-subtitles/* subtitles/wowinsight/
```

### 阶段 3: 清理
```bash
# 删除空目录
rmdir bestpartners-subtitles
rmdir diaryofaceo-subtitles
rmdir wowinsight-subtitles
```

---

## 📊 统计

- **字幕文件**: 400+ 个
- **频道数**: 3 个
- **分类**: 已完成

---

**状态**: 🔄 整理中
