# Skill-Derived Production Brief

> Reusable production prompt synthesized from the user's explicit decisions and the `edit-timeline-studio` workflow. This is not the user's verbatim prompt, a system prompt, or hidden chain-of-thought.

## English prompt

```text
Use the edit-timeline-studio skill to create an editing-style reference replication.

INPUTS
- Reference video: {{REFERENCE_VIDEO_PATH}}
- Subject: {{SUBJECT_NAME}}
- Authorized replacement footage: {{LOCAL_ASSET_PATHS_OR_APPROVED_SOURCE_SCOPE}}
- Output directory: {{OUTPUT_DIRECTORY}}

CREATIVE GOAL
Recreate the reference video's transferable editing grammar with {{SUBJECT_NAME}} footage:
shot placement, subject scale, repeated-shot structure, black-frame punctuation, flashes,
blur impacts, speed changes, word/beat timing, climax density, and final-card behavior.
Do not copy protected branding or use footage without a lawful usage basis.

HARD INVARIANTS
- Preserve the authorized original audio track exactly at the original source time.
- Match the reference duration and frame rate unless analysis proves a required exception.
- Keep a 720×1280 portrait container.
- Rotate the main landscape composition sideways for turn-the-phone viewing.
- Return the final title card to an upright portrait orientation.
- Use at least {{MIN_VARIANTS}} visually distinct {{SUBJECT_NAME}} variants/outfits/forms.
- Formal shots must be HD CG or clean cinematic footage: no low-resolution GIFs, no HUD,
  no unrelated characters, no baked subtitles, and no visible third-party watermarks.

ANALYSIS
1. Preserve this prompt verbatim as the creative brief.
2. Inspect the full reference and build an audio clock, shot/sub-shot table, repetition graph,
   temporal-operation map, look-state timeline, transition map, subject-geometry track,
   and setup/rise/pre-impact/peak/aftershock beat map.
3. Do not edit until every reference interval has a reconstruction role and acceptance criteria.

FOOTAGE SOURCING
- Prefer user-supplied media, first-party media libraries, official downloadable files, and
  sources with explicit usage terms.
- Record source URL, provider, usage basis, resolution, access date, and selected intervals.
- Do not use third-party downloaders, bypass disabled download controls, or treat public
  streaming availability as reuse permission.
- If compliant HD coverage is missing, report the exact gap before generating or substituting.

EDITING
- Map replacement clips by dramatic function, not by original-file order.
- Place variant changes on structural turns, black cards, flashes, or peaks.
- Preserve intentional repetition, but give later recurrences a reminder, escalation,
  comparison, acceleration, or climax function.
- Protect the clearest hero frame at the primary peak.
- Keep character identity exclusive to {{SUBJECT_NAME}} unless another character is explicitly approved.
- Treat every user correction as a surgical revision: replace the complete affected beat while
  preserving global frame count, duration, audio clock, and unaffected intervals.

DELIVERABLES
- {{OUTPUT_DIRECTORY}}/{{PROJECT_SLUG}}.timeline
- {{OUTPUT_DIRECTORY}}/{{PROJECT_SLUG}}.mp4
- A contact sheet, source/provenance manifest, and verification report.

VALIDATION
- Reopen the .timeline and verify media resolution and track state.
- Fully decode the MP4.
- Verify dimensions, frame rate, frame count, duration, audio presence, final orientation,
  every cut/transition, repeated-shot order, subject identity, and hero-frame clarity.
- When original audio is retained without re-encoding, compare the reference and result
  audio bitstream hashes.
- Reject completion for an unrelated character, low-quality source, missing editable project,
  unexplained interval, flattened repetition, timing drift, or obscured primary peak.
```

## 中文提示词

```text
使用 edit-timeline-studio skill 完成一次剪辑风格参考复刻。

输入
- 参考视频：{{REFERENCE_VIDEO_PATH}}
- 主体角色：{{SUBJECT_NAME}}
- 已授权替换素材：{{LOCAL_ASSET_PATHS_OR_APPROVED_SOURCE_SCOPE}}
- 输出目录：{{OUTPUT_DIRECTORY}}

创作目标
使用 {{SUBJECT_NAME}} 素材复刻参考片可迁移的剪辑语法：镜头位置、人物比例、
重复镜头结构、黑场断句、闪白、模糊冲击、变速、文字/节拍同步、高潮密度和尾卡行为。
不要复制受保护的品牌身份，也不要使用缺少合法使用依据的素材。

硬约束
- 在原始时间位置完整保留经授权的原音轨。
- 除非分析证明必须调整，否则保持参考片时长与帧率。
- 使用 720×1280 竖屏容器。
- 主体横版画面整体侧躺，供观众横转手机观看。
- 最终尾卡恢复为正向竖屏。
- 至少使用 {{MIN_VARIANTS}} 套视觉差异明确的 {{SUBJECT_NAME}} 形态/皮肤/装甲。
- 正式镜头必须为高清 CG 或干净电影感素材：禁止低清 GIF、HUD、无关人物、
  素材自带字幕和第三方水印。

分析
1. 将本提示词原样保存为创作 brief。
2. 完整分析参考片，建立音频时钟、镜头/子镜头表、重复关系图、时间操作图、
   视觉状态时间线、转场图、主体几何轨迹，以及建立/上升/冲击前/高潮/余波节拍图。
3. 每个参考片区间都有重建角色和验收标准后，才能开始剪辑。

素材检索
- 优先使用用户素材、第一方媒体库、官方可下载文件和有明确使用条款的来源。
- 记录来源 URL、提供方、使用依据、分辨率、访问日期和采用区间。
- 禁止使用第三方下载器、绕过关闭的下载控制，或把“公开可播放”当成复用授权。
- 合规高清素材不足时，先报告具体缺口，不要擅自生成或替代。

剪辑
- 按戏剧功能映射镜头，不按源文件顺序简单拼接。
- 把形态切换放在结构转折、黑卡、闪白或高潮上。
- 保留参考片有意义的重复，但让后续重复承担提醒、升级、对比、加速或高潮功能。
- 保护主高潮最清晰的英雄帧。
- 除非明确批准，所有人物镜头只能出现 {{SUBJECT_NAME}}。
- 用户提出视觉修正时，整段替换受影响的节拍，同时保持总帧数、时长、音频时钟
  和其他区间不变。

交付物
- {{OUTPUT_DIRECTORY}}/{{PROJECT_SLUG}}.timeline
- {{OUTPUT_DIRECTORY}}/{{PROJECT_SLUG}}.mp4
- 接触表、素材来源清单和验证报告。

验收
- 重新打开 .timeline，检查媒体解析与轨道状态。
- 完整解码 MP4。
- 检查尺寸、帧率、帧数、时长、音轨、最终方向、所有切点/转场、重复顺序、
  人物身份和高潮英雄帧清晰度。
- 原音无重编码保留时，对比参考片与成片音频比特流哈希。
- 出现无关人物、低质素材、缺失可编辑工程、未解释区间、重复关系被抹平、
  节拍漂移或主高潮被遮挡时，拒绝交付。
```

## Variables used by this case

| Variable | Value |
| --- | --- |
| `SUBJECT_NAME` | Kiana Kaslana / 琪亚娜·卡斯兰娜 |
| `MIN_VARIANTS` | 4 |
| `PROJECT_SLUG` | `kiana-multi-battlesuit-remake` |
| Target duration | 26.466667 seconds |
| Target frame count | 794 at 30 fps |
