# 职涯 · 模拟面试官

> 简历优化 + 结构化模拟面试

基于用户目标岗位，自动优化简历并模拟真实结构化面试流程。适用于求职者模拟练习、HR面试官培训等场景。

## 功能特性

- 根据目标岗位 JD 优化简历内容与措辞
- 基于简历生成结构化面试问题
- 模拟真实面试问答流程
- 给出面试表现评估与改进建议

## 项目结构

```
├── README.md
├── .gitignore
├── agent/
│   ├── prompt.md          # 系统提示词 / 人设
│   └── config.yaml        # 智能体元信息
├── workflows/
│   └── README.md          # 工作流说明（导出 JSON 放此目录）
└── knowledge/
    └── README.md          # 知识库说明（文档放此目录）
```

## 平台

基于 [Coze（扣子）](https://www.coze.com) 构建。

## 快速开始

1. 在 Coze 中创建智能体
2. 将 `agent/prompt.md` 内容填入「人设与回复逻辑」
3. 导入 `workflows/` 下的工作流 JSON
4. 配置 `knowledge/` 下的知识库文档

## 目录说明

| 目录 | 内容 |
|------|------|
| `agent/` | 提示词、人设、智能体配置 |
| `workflows/` | 工作流导出文件（.json） |
| `knowledge/` | 知识库文档、FAQ、规则文件 |
