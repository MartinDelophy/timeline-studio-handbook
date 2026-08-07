# Timeline Studio Skill Cases

> Reproducible AI video-editing workflows, result cases, and evaluation criteria.

English · [简体中文](README.zh-CN.md) · [Contributing](CONTRIBUTING.md)

![Cases](https://img.shields.io/badge/cases-5-ff6b35) ![Skill](https://img.shields.io/badge/skill-edit--timeline--studio-7c3aed)

> These Skills are executed by [Timeline Studio — the open-source AI video editor](https://github.com/MartinDelophy/ai-video-editor).
>
> Want to run any case? [Install Timeline Studio](https://github.com/MartinDelophy/ai-video-editor) first.

One prompt. One result. One editable `.timeline` project.

## What this repository proves

- **Reproducible workflows:** each case preserves its one-line prompt, original video when available, result video, and editable project.
- **Visible results:** compact previews make the outcome understandable before the implementation details.
- **Verifiable evaluation:** compare prompt adherence and reference similarity, inspect audiovisual quality, and open the `.timeline` to examine the edit structure.

## Case 001 · Original → Result

[![Original and skill result shown side by side](cases/001-kiana-multi-battlesuit-remake/assets/comparison.webp)](cases/001-kiana-multi-battlesuit-remake/README.md)

> Recreate this reference as a Kiana video with extremely similar framing and editing, using multiple battlesuits and HD CG footage.

[Original video](cases/001-kiana-multi-battlesuit-remake/assets/reference.mp4) → [Result video](cases/001-kiana-multi-battlesuit-remake/assets/result.mp4) · [Editable `.timeline`](cases/001-kiana-multi-battlesuit-remake/assets/kiana-multi-battlesuit-remake.timeline) · [Open case](cases/001-kiana-multi-battlesuit-remake/README.md)

## Case 002 · Prompt → Result

[![Claude Fable 5 promotional video](cases/002-claude-fable-5-promo/assets/preview.webp)](cases/002-claude-fable-5-promo/README.md)

> Create a promotional video for Claude Fable 5 using `edit-timeline-studio`.

[Result video](cases/002-claude-fable-5-promo/assets/result.mp4) · [Editable `.timeline`](cases/002-claude-fable-5-promo/assets/claude-fable-5-promo.timeline) · [Open case](cases/002-claude-fable-5-promo/README.md)

## Case 003 · Chinese → English

[![Chinese original and English result shown side by side](cases/003-claude-fable-5-english-localization/assets/comparison.webp)](cases/003-claude-fable-5-english-localization/README.md)

> Convert the Claude Fable 5 promo entirely to English, using an English-only voiceover.

[Chinese original](cases/002-claude-fable-5-promo/assets/result.mp4) → [English result](cases/003-claude-fable-5-english-localization/assets/result.mp4) · [Editable `.timeline`](cases/003-claude-fable-5-english-localization/assets/claude-fable-5-english.timeline) · [Open case](cases/003-claude-fable-5-english-localization/README.md)

## Case 004 · Prompt → Narrative Promo

[![Product, tutorial, and personal-story proof cases](cases/004-everyone-can-create-narrative/assets/preview.webp)](cases/004-everyone-can-create-narrative/README.md)

> Create a promotional video around this idea: creating content is easier than ever, and manual editing is becoming the old way.

[Result video](cases/004-everyone-can-create-narrative/assets/result.mp4) · [Editable `.timeline`](cases/004-everyone-can-create-narrative/assets/everyone-can-create.timeline) · [Open case](cases/004-everyone-can-create-narrative/README.md)

## Case 005 · Prompt → Cosmic Science Video

[![Cosmic scale science video](cases/005-cosmic-scale-science/assets/preview.webp)](cases/005-cosmic-scale-science/README.md)

> Create a stunning, easy-to-understand cosmic science video using web-sourced footage.

[Result video](cases/005-cosmic-scale-science/assets/result.mp4) · [Editable `.timeline`](cases/005-cosmic-scale-science/assets/cosmic-scale.timeline) · [Open case](cases/005-cosmic-scale-science/README.md)

## The two formats

| Type | What visitors see |
| --- | --- |
| **Comparison** | Original video → one-line prompt → result video |
| **Standalone** | One-line prompt → result video |

Every case also includes its `.timeline` project so the result is backed by an editable artifact, not just a claim.

## Add a case

Use the [minimal case template](cases/_template/README.md) and follow the [contribution guide](CONTRIBUTING.md). Browse all cases in the [case gallery](cases/README.md).

## Rights

This is an unofficial, non-commercial skill demonstration. Third-party media remains the property of its respective owners and is excluded from the repository's [CC BY 4.0 license](LICENSE).
