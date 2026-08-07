# Timeline Studio Handbook

> 我使用 Timeline Studio 进行 AI 辅助视频创作、自动剪辑与交付复盘的个人实践手册。

[English](README.md) · 简体中文

[工作流](docs/workflow.zh-CN.md) · [效果展示](showcases/README.zh-CN.md) · [参与贡献](CONTRIBUTING.zh-CN.md)

## 这是什么

这个仓库记录的不是一份功能清单，而是一套可以复用、验证和持续改进的 Timeline Studio 使用方式：如何从素材和目标出发，组织时间线、使用 AI 辅助能力、控制质量，并把最终效果连同过程一起沉淀下来。

仓库当前处于起步阶段。首要目标是建立清晰的记录格式，之后逐步补充真实项目、提示词、时间线拆解和导出结果。

> [!NOTE]
> 这是非官方的个人实践仓库，与 Timeline Studio 项目维护团队没有隶属关系。产品能力与界面可能随版本变化，请以[官方仓库](https://github.com/chatman-media/timeline-studio)为准。

## 为什么做这个仓库

- 记录一套从需求到成片的稳定流程，而不只是零散技巧。
- 用真实效果展示方法是否有效，并保留关键参数与取舍。
- 沉淀失败案例和排错经验，减少重复试错。
- 让其他使用者可以复现、讨论并贡献自己的工作流。

## 我的基本方法

```text
明确目标 → 整理素材 → 设计节奏 → AI 辅助粗剪 → 人工精修 → 质量检查 → 导出与复盘
```

我会优先关注四件事：

1. **目标先行**：先确定平台、受众、时长和观看场景，再决定比例与节奏。
2. **AI 做高杠杆工作**：让 AI 参与素材理解、粗剪、转录和版本适配；叙事判断与最终审美由人完成。
3. **过程可复现**：案例尽量记录工具版本、输入素材、关键操作、提示词和导出设置。
4. **结果可比较**：展示成片的同时，也说明修改前后、耗时、有效之处和局限。

完整步骤见[我的 Timeline Studio 工作流](docs/workflow.zh-CN.md)。

## 效果展示

效果展示是本仓库的重点。每个案例都会尽量包含：

- 成片或可直接预览的 GIF/截图；
- 项目目标、平台与目标时长；
- 素材类型和时间线结构；
- 使用到的 AI 能力、提示词与人工调整；
- 导出参数、制作耗时和复盘结论。

当前案例正在整理中。你可以从[展示索引](showcases/README.zh-CN.md)查看进度，也可以复制[案例模板](showcases/_template/README.zh-CN.md)提交自己的作品。

| 案例 | 类型 | 目标 | 状态 |
| --- | --- | --- | --- |
| 首个完整工作流案例 | 待定 | 展示从素材到成片的完整过程 | 准备中 |

## 仓库结构

```text
timeline-studio-handbook/
├── README.md                 # 项目入口
├── docs/
│   └── workflow.md           # 我的完整工作流
├── showcases/
│   ├── README.md             # 案例索引与收录标准
│   └── _template/README.md   # 新案例模板
├── CONTRIBUTING.md           # 贡献指南
├── CODE_OF_CONDUCT.md        # 社区行为准则
└── .github/                  # Issue 与 Pull Request 模板
```

## 开始阅读或参与

- 想了解方法：从[工作流](docs/workflow.zh-CN.md)开始。
- 想看效果：前往[效果展示](showcases/README.zh-CN.md)。
- 想分享经验：阅读[贡献指南](CONTRIBUTING.zh-CN.md)，然后提交 Issue 或 Pull Request。
- 发现描述与当前版本不符：请提交“文档修正”Issue，并附上 Timeline Studio 版本和操作系统。

## 路线图

- [x] 建立仓库结构与贡献规范
- [x] 发布可复用的工作流和案例模板
- [ ] 加入第一个完整的效果展示
- [ ] 增加常用提示词与参数记录
- [ ] 增加常见问题和故障排查
- [ ] 根据真实案例整理不同平台的导出策略

## 致谢与参考

- [Timeline Studio](https://github.com/chatman-media/timeline-studio)：本手册所使用的开源视频编辑项目。
- [GitHub Community Standards](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions)：仓库协作文件与贡献流程参考。
- [Standard Readme](https://github.com/RichardLitt/standard-readme)：README 信息结构参考。

## 许可

除另有说明外，本仓库的文字、图片和案例说明采用 [CC BY 4.0](LICENSE) 许可。案例中引用的第三方素材仍归原权利人所有，请在提交内容时注明来源和授权情况。
