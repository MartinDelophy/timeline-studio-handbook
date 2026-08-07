# Awesome Timeline Studio Skills

> 使用 Timeline Studio Skills 产出的真实案例、可复用提示词与可验证结果。

[English](README.md) · 简体中文

[案例画廊](cases/README.zh-CN.md) · [Skill 工作流](docs/workflow.zh-CN.md) · [参与贡献](CONTRIBUTING.zh-CN.md)

![案例数](https://img.shields.io/badge/cases-1-ff6b35) ![Skills](https://img.shields.io/badge/skills-1-7c3aed) ![语言](https://img.shields.io/badge/language-English%20%7C%20中文-0ea5e9)

## 精选案例

[![琪亚娜多装甲参考视频复刻](cases/001-kiana-multi-battlesuit-remake/assets/preview.webp)](cases/001-kiana-multi-battlesuit-remake/README.zh-CN.md)

### Case 001 — 琪亚娜多装甲参考视频复刻

`edit-timeline-studio` skill 对一条 26.47 秒参考视频进行逆向分析，检索来源可追溯的高清素材，重建“竖屏容器中横画面侧躺”的视觉语法，混剪琪亚娜多套装甲，并根据用户反馈持续修正人物身份与重复镜头。

| Skill | 核心能力 | 结果 | 提示词包 |
| --- | --- | --- | --- |
| `edit-timeline-studio` | 参考片分析、合规素材检索、镜头功能映射、节拍级组装、迭代式视觉 QA、技术验收 | [查看案例](cases/001-kiana-multi-battlesuit-remake/README.zh-CN.md) · [观看 MP4](cases/001-kiana-multi-battlesuit-remake/assets/result.mp4) · [下载 `.timeline`](cases/001-kiana-multi-battlesuit-remake/assets/kiana-multi-battlesuit-remake.timeline) | [原始需求](cases/001-kiana-multi-battlesuit-remake/prompts/00-original-brief.md) · [Skill 制作提示词](cases/001-kiana-multi-battlesuit-remake/prompts/01-production-brief.md) |

## 项目理念

这个仓库把 Agent Skill 看作一套生产系统，而不只是一份简短指令。每个案例连接四个部分：

```text
用户意图 → Skill 工作流 → Skill 生成的制作提示词 → 可验证输出
```

目标是让 Skill 能力既能被看见，也能被复用：

- **结果优先**：每个案例先展示作品，再描述能力。
- **提示词即生产代码**：同时保存用户原始需求，以及使用 Skill 后整理出的结构化制作 brief。
- **证据代替形容词**：记录帧数、时长、尺寸、音频校验、来源和已知限制。
- **迭代也是案例的一部分**：用户的修正意见和对应版本变化不会被隐藏。
- **结构可扩展**：以后可以持续加入新的 session，而不必重做仓库结构。

## Skill 能力索引

| Skill | 案例数 | 已展示能力 | 案例 |
| --- | ---: | --- | --- |
| `edit-timeline-studio` | 1 | 帧级参考复刻、网络素材研究、多源剪辑、反馈驱动修订、交付 QA | [Case 001](cases/001-kiana-multi-battlesuit-remake/README.zh-CN.md) |

后续完成的其他 Skill 和多 Skill 组合工作流都会继续加入这里。

## 案例组成

每个案例应当包含：

1. **结果**：可直接查看的预览，以及完整或适合仓库存储的成片。
2. **Session 上下文**：session ID、原始请求、素材约束和关键用户修正。
3. **使用的 Skills**：Skill 名称与实际展现的生产能力。
4. **提示词包**：用户原始 brief，以及通过 Skill 工作流整理出的可复用制作提示词。
5. **过程**：重要决策、迭代和被放弃的方案。
6. **验证**：媒体参数、技术检查和验收证据。
7. **来源与限制**：素材链接、权利说明、缺失产物和真实边界。

浏览[完整案例画廊](cases/README.zh-CN.md)，或使用[案例模板](cases/_template/README.zh-CN.md)。

## 如何使用

1. 找到效果与你目标接近的案例。
2. 阅读能力表和制作决策。
3. 复制案例中的 Skill 制作提示词，并替换变量。
4. 使用你有权处理的素材调用相应 Skill。
5. 根据案例中的验收标准检查结果。

## 仓库结构

```text
timeline-studio-handbook/
├── README.md                         # 英文优先的画廊首页
├── README.zh-CN.md                   # 完整简体中文镜像
├── cases/
│   ├── README.md                     # 案例索引
│   ├── _template/                    # 后续 session 的统一模板
│   └── 001-kiana-multi-battlesuit-remake/
│       ├── README.md                 # 案例说明
│       ├── prompts/                  # 原始与 Skill 生成提示词
│       └── assets/                   # 预览、接触表与成片
├── docs/                             # 通用工作流
└── CONTRIBUTING.md                   # 贡献规则
```

## 路线图

- [x] 将手册升级为结果优先的 Skill 案例库
- [x] 加入第一个真实 Codex session 和提示词包
- [x] 加入适合 GitHub 展示的图片与视频预览
- [ ] 增加更多 `edit-timeline-studio` 工作流
- [ ] 增加多 Skill 组合生产案例
- [ ] 按 Skill、媒体类型和能力提供筛选
- [ ] 案例数量足够后增加可视化画廊网站

## 说明与免责声明

这是非官方个人实践仓库，与 Timeline Studio 维护团队、HoYoverse 或米哈游没有隶属关系。产品行为可能随版本变化，请以 [Timeline Studio 官方仓库](https://github.com/chatman-media/timeline-studio)为准。

案例媒体可能包含第三方素材，仅用于非商业的 Skill 能力展示和方法研究，并保留来源说明；相关权利归各自权利人所有。不要默认案例媒体可以用于商业用途。

## 许可

除另有说明外，原创文档和提示词结构采用 [CC BY 4.0](LICENSE) 许可。第三方媒体和引用素材不包含在该许可中。
