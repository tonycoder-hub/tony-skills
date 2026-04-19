# Tony Skills

个人 Agent Skills 仓库。

这个仓库用于独立管理可复用的个人 Skill，避免与具体业务项目混放。目录设计保持普通、直接，clone 后可以按常规仓库方式浏览、编辑和维护。

## 当前内容

- `thought-to-output/`：把语音转文字、碎片笔记和发散表达整理为结构化输出

## 推荐目录结构

```text
tony-skills/
├── README.md
├── LICENSE.md
├── .gitignore
└── thought-to-output/
    ├── SKILL.md
    ├── README.md
    ├── references/
    │   ├── output-categories.md
    │   └── quality-checklist.md
    └── assets/
        └── sample-outputs.md
```

## 使用方式

1. clone 仓库到本地
2. 进入目标 Skill 目录
3. 查看 `SKILL.md` 获取 Skill 定义和主说明
4. 参考 `references/` 和 `assets/` 里的补充材料进行扩展或复用

## 命名约定

- 每个 Skill 使用一个独立目录
- Skill 目录内至少包含一个 `SKILL.md`
- 参考材料放在 `references/`
- 示例内容放在 `assets/`

## 备注

- 当前仓库以中文内容为主
- 默认不依赖脚本和联网
- 当前版权说明见 `LICENSE.md`
