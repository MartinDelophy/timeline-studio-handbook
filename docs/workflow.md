# My Timeline Studio Workflow

[English](workflow.md) · [简体中文](workflow.zh-CN.md)

This workflow is intended for short-form video, product demos, tutorials, and montages. It makes content decisions first and uses automation for repetitive work.

## 1. Define the deliverable

Before importing media, write down:

- publishing platform and aspect ratio;
- audience and desired viewer action;
- target duration and information density;
- required shots, text, or brand elements;
- deadline and acceptable quality boundary.

A useful one-sentence brief is:

> Turn **[source material]** into a **[duration/aspect ratio]** video for **[audience]**, so viewers understand **[core message]** and take **[action]**.

## 2. Organize source material

Organize files by purpose rather than origin:

```text
project-name/
├── footage/       # Primary and supporting shots
├── audio/         # Voice, music, and sound effects
├── graphics/      # Logos, screenshots, and illustrations
├── references/    # Style and pacing references
└── exports/       # Rendered results
```

Check licensing, resolution, frame rate, audio quality, and sensitive information before importing.

## 3. Build the story before polishing

Use markers or text to establish the hook, context, key message, evidence/demo, and call to action. During the rough cut, ask only whether each segment serves the goal. Leave frame-level tuning and complex effects for later.

## 4. Use AI for the rough cut

Good AI-assisted tasks include:

- transcription, summarization, and segmentation;
- identifying pauses, repetition, and highlight candidates;
- proposing cuts for a target duration;
- drafting captions and platform variants;
- suggesting structural changes to an existing timeline.

Include the goal, constraints, and protected content in a prompt:

```text
Turn this interview into a 60-second vertical video. Keep the product demo and final conclusion;
remove repeated ideas and long pauses. Lead with the result in the first three seconds. Do not
change the speaker's meaning, and flag any proper noun you cannot verify.
```

Treat AI output as a draft. Facts, speaker intent, brand rules, and copyright always require human review.

## 5. Refine manually

Work in this order to reduce rework:

1. Narrative — completeness, opening speed, and a clear ending.
2. Rhythm — remove meaningless pauses while preserving room for key moments.
3. Picture — framing, crops, transitions, and supporting footage.
4. Sound — speech clarity, music hierarchy, loudness, and abrupt changes.
5. Captions — line breaks, names, occlusion, and safe areas.
6. Visual consistency — typography, color, animation speed, and branding.

## 6. Run pre-export QA

- Watch once from beginning to end without scrubbing.
- Watch muted to verify that visuals and captions still communicate.
- Listen without watching to catch cuts, noise, and volume jumps.
- Check the first frame, final frame, spelling, links, and calls to action.
- Preview on the target device or platform for aspect ratio, clarity, and safe areas.
- Keep one high-quality master, then derive platform-specific versions.

## 7. Review and record

Record total time, steps saved by AI, the biggest source of rework, audience feedback or metrics, and what to keep or change next time. Use the [showcase template](../showcases/_template/README.md) to archive the process with the result.

## Working principles

- More automation requires clearer acceptance criteria.
- Keep one timeline as the single current source of truth.
- Solve content problems before visual problems.
- Settings are context; the result and reproducibility are the conclusion.
