# Case 012 · 15-Second Memory Highlight Recut

`Comparison` · `edit-timeline-studio` · Built with [Timeline Studio](https://github.com/MartinDelophy/ai-video-editor) · [简体中文](README.zh-CN.md)

## 1. Original footage

[Watch the primary source video](assets/reference.mp4)

## 2. One-line prompt

> Turn my source footage into a 15-second memory highlight: cut multiple beat-synced flashbacks to the music peak around 1:20, add a midpoint flash transition, and use 2:48–2:51 from the second clip as the final three seconds.

## 3. Result

[![Original footage and 15-second highlight result shown side by side](assets/comparison.webp)](assets/result.mp4)

[Watch the result video](assets/result.mp4) · [Download the editable `.timeline` project](assets/memory-highlight-recut.timeline)

The final 15.00-second edit condenses the primary source into eight short memory fragments, then replaces 12.00–15.00 with the requested embrace from a second source clip. The source audio is muted throughout; a separately supplied track contributes only its 80.50–95.50 music highlight. A brief white flash marks the midpoint, while the last 0.70 seconds fade cleanly to black. The 1906×1080, 29 fps H.264/AAC result and the nine-clip project passed full decode and archive validation.

The published `.timeline` deduplicates identical embedded source bytes while preserving every clip ID, source-time range, music asset, and edit decision.

Session: `01a02866-7693-7721-973f-dc529adbf70b`
