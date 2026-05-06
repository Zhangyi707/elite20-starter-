# D5 - Skill与食谱卡片

**日期**：2026年5月6日
**学员**：张老师（大学英语教师）

---

## 今日主题

**调用和阅读Skills（SKILL.md）**

了解如何使用预构建的Skills，让AI更好地完成特定任务。

---

## Skills调用记录

### Skill 1: Translator Pro 翻译专家

**使用场景**：翻译大学英语四级阅读文章

**调用方式**：
```
使用 Translator Pro 技能翻译一篇英语文章
```

**执行过程**：
```
1. 加载Translator Pro技能
2. 输入英文原文
3. 选择中英对照模式
4. 获取多译本对比输出
5. 导出为Markdown格式
```

**输出结果**：
```
## 原文
The rapid advancement of artificial intelligence has transformed various sectors,
including education. In language learning, AI-powered tools offer personalized
feedback and adaptive learning paths that were previously unavailable.

## 译文
人工智能的快速发展已经改变了包括教育在内的多个行业。
在语言学习方面，AI驱动的工具提供了以前无法实现的个性化反馈和自适应学习路径。

## 术语表
- artificial intelligence: 人工智能 (AI)
- personalized feedback: 个性化反馈
- adaptive learning: 自适应学习
```

**质量评估**：✅ 可用
**优点**：术语准确、保持学术风格、多译本对比
**改进点**：可增加文化注释

---

### Skill 2: docx (Word文档处理)

**使用场景**：创建标准化教案模板

**调用方式**：
```
使用docx技能生成一份英语教案Word文档
```

**输出结果**：
生成了一份包含以下结构的教案模板：
- 教学目标
- 教学内容
- 教学步骤
- 课堂活动
- 作业布置
- 教学反思

**质量评估**：✅ 可用
**优点**：格式规范、可直接打印使用

---

## SKILL.md阅读笔记

**阅读的SKILL.md文档**：Translator Pro 翻译专家

**主要内容总结**：
1. **多译本对比**：提供直译/意译/学术翻译三个版本
2. **术语表**：自动提取专业术语并给出标准翻译
3. **本地化校對**：考虑中文表达习惯进行调整
4. **批量翻译**：支持一次处理多个段落

**可应用于教学的启发**：
作为英语教师，可以用Translator Pro快速翻译英文教学材料，同时保留术语对照，便于学生理解专业词汇。

---

## Skill生成的作品

**已完成的作品**：大学英语教案模板.docx
- 文件名：大学英语教案模板.docx
- 存放位置：deliverables/D7_英语教学资源包/
- AI辅助成分：使用docx技能生成，包含标准化教案结构

---

## 3行反思

**我学到了什么**
Skills是预构建的专业工作流，比单纯聊天更可靠。今天我体验了Translator Pro的多译本对比功能，这比我自己翻译更系统、更全面。

**我的感受**
作为英语教师，我一直自己翻译教学材料。现在有了专业Skills，我可以将翻译工作交给AI，节省的时间可以用于教学设计。

**我的下一步**
1. 整理一份个人英语教学术语表
2. 探索用Translator Pro翻译考试真题
3. 尝试用docx技能批量生成教案模板