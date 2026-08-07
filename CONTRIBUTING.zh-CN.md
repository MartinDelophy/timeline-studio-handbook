# 参与贡献

[English](CONTRIBUTING.md) · 简体中文

感谢你帮助完善 Timeline Studio Skill 案例库。这里欢迎真实、效果可直接验证的 Skill session。

## 可以贡献什么

- **Skill 案例**：包含一句话提示词、结果和可编辑 `.timeline` 工程的真实 session。
- **提示词包**：用户原始 brief，以及清楚标注为 Skill 生成或整理的可复用提示词。
- **工作流**：适用于某类内容或平台的可复现方法。
- **经验修正**：对版本变化、错误说明或过时步骤的更新。
- **资源完善**：在版权允许的前提下补充截图、示例或参考资料。

## 提交前

1. 搜索现有 Issues 和 Pull Requests，避免重复。
2. 确认内容不包含 API 密钥、隐私数据或保密信息。
3. 确认你有权公开提交的文字、图片、视频、音乐和字体。
4. 对产品行为的描述注明 Timeline Studio 版本和操作系统。
5. 案例请从 `cases/_template` 复制模板，不要直接修改模板本身。

## 本地流程

```bash
git clone https://github.com/<owner>/timeline-studio-handbook.git
cd timeline-studio-handbook
git checkout -b docs/short-description
```

编辑后检查 Markdown 链接、图片路径和拼写，再提交：

```bash
git add <changed-files>
git commit -m "docs: describe the change"
git push -u origin docs/short-description
```

随后创建 Pull Request，并在描述中说明修改内容、原因和验证方式。

## 案例目录约定

- 目录名使用编号加小写 kebab-case，例如 `002-interview-to-shorts`。
- 每个案例必须同时包含 `README.md` 和 `README.zh-CN.md`。
- 主展示保持极简：有原视频就放原视频，再放一句话提示词、结果视频和 `.timeline` 工程佐证。
- 有原视频时归类为**对比型**，没有原视频时归类为**生成型**。
- 更长的提示词包可以作为补充材料，但不要放进主阅读路径。
- 可以保留用户明确输入，但不得公开隐藏推理、凭据、密钥、个人信息或私有本地路径。
- 必须明确区分用户原始提示词和由 Skill 或维护者整理的衍生提示词。
- 本地媒体放在案例自身的 `assets/` 下，不要引用个人电脑的绝对路径。
- 优先提交 WebP/JPEG 图片和短 GIF；大视频使用外部链接。
- 不接受只有宣传链接、没有过程和验证证据的案例。

## 写作约定

- 英文为默认版本，并同步维护完整的简体中文版本。
- 直接写清楚版本、操作和结果，避免无法验证的绝对化结论。
- 命令、文件名和界面字段使用反引号。
- 外部内容使用链接并注明来源，避免复制大段原文。

## Pull Request 检查清单

- [ ] 修改聚焦于一个主题。
- [ ] 所有相对链接和图片路径有效。
- [ ] 产品行为注明了版本与环境。
- [ ] 案例素材已获授权且标注来源。
- [ ] 没有提交个人信息、密钥或大体积原始文件。
- [ ] 已更新案例索引、Skill 能力索引和中英文版本。

参与本仓库即表示你同意遵守[社区行为准则](CODE_OF_CONDUCT.zh-CN.md)，并同意以仓库许可证发布你的贡献。
