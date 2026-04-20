# Thought to Output

个人 Agent Skill：将语音转文字、碎片笔记和发散表达整理为结构化内容或完整文章。

## 核心能力

- 短输入 → 结构化卡片（主线 + 摘要 + 行动项）
- 长输入 / 个人反思类 → 完整成稿（带标题的长文）
- 自动判断输出形态，也支持用户手动指定

## 目录结构

```
thought-to-output/
├── SKILL.md                          # Skill 主定义（触发条件、工作流、输出格式）
├── README.md                         # 本文件
├── references/
│   ├── output-categories.md          # 输出类别定义
│   └── quality-checklist.md          # 质量检查清单
└── assets/
    └── sample-outputs.md             # 输入输出示例（含短输入卡片和长输入成稿）
```

## 使用方式

1. 查看 `SKILL.md` 获取完整定义
2. 参考 `references/` 了解输出类别和质量标准
3. 参考 `assets/sample-outputs.md` 查看具体示例

## 设计原则

- 去重不去细节：删除重复表述，但保留具体的人、事、物、场景
- 按量级自动切换：短输入出卡片，长输入出文章
- 多主题用暗线串联，不强行压成单主线
- 保留用户语气和第一人称视角
- 宁可少输出，也不硬凑类别
