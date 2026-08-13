# Handout Generator

讲义批量生成器 - 将 Markdown 文档转换为统一格式的 HTML 讲义

## 功能
- 📝 粘贴 Markdown 内容
- 🎨 自动套用专业讲义模版（Bookstore 风格）
- 👁️ 实时预览
- 💾 一键下载 HTML
- 🖨️ 打印优化（A4）

## Markdown 输入规范

```markdown
# 讲义标题

## Reading
阅读材料正文...

## Analysis
### 段落1标题
分析内容...

### 段落2标题
分析内容...

## Task 1: 任务名称
任务说明文字

### Practice A: 基础练习
练习内容...

### Practice B: 进阶练习
练习内容...

### Practice C: 综合练习
练习内容...

### Practice D: 创意练习
练习内容...

## Task 2: 任务名称
...
```

## 技术栈
- 纯静态 HTML（无构建步骤）
- Marked.js（Markdown 解析）
- 模版样式复刻自 Bookstore-Exercise.html
