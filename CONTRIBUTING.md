# Contributing

English · [简体中文](CONTRIBUTING.zh-CN.md)

Thank you for improving Timeline Studio Skill Cases. We welcome real, visually verifiable skill sessions.

## Ways to contribute

- **Cases** — real skill sessions with a one-line prompt, result, and editable `.timeline` project.
- **Prompt packs** — original user briefs plus clearly labeled reusable prompts produced through skill use.
- **Workflows** — reproducible methods for a content type or platform.
- **Corrections** — updates for version changes, inaccurate claims, or outdated steps.
- **Supporting material** — screenshots, examples, or references that you have permission to share.

## Before submitting

1. Search existing Issues and Pull Requests to avoid duplicates.
2. Remove API keys, private data, and confidential information.
3. Confirm that you may publish every contributed text, image, video, music track, and font.
4. Include the Timeline Studio version and operating system for product behavior.
5. Copy `cases/_template`; do not edit the template itself for a new case.

Core documentation should remain available in both English and Simplified Chinese. English is the default version; update its Chinese counterpart in the same Pull Request when changing shared meaning.

## Local workflow

```bash
git clone https://github.com/<owner>/timeline-studio-handbook.git
cd timeline-studio-handbook
git checkout -b docs/short-description
```

Check Markdown links, image paths, and spelling before committing:

```bash
git add <changed-files>
git commit -m "docs: describe the change"
git push -u origin docs/short-description
```

Then open a Pull Request that explains what changed, why, and how it was verified.

## Case conventions

- Use a numbered lowercase kebab-case directory such as `002-interview-to-shorts`.
- Every case must contain both `README.md` and `README.zh-CN.md`.
- Keep the main display simple: original video when available, one-line prompt, result video, and `.timeline` evidence.
- Classify the case as **Comparison** when an original exists, otherwise **Standalone**.
- Longer prompt packs are optional supporting material, not part of the main reading path.
- Preserve explicit user requests, but never publish hidden reasoning, credentials, secrets, personal data, or private local paths.
- Clearly distinguish user-authored prompts from prompts synthesized by a skill or maintainer.
- Store local media under the case's own `assets/` directory. Never use absolute paths from your computer.
- Prefer compressed WebP/JPEG images and short GIFs; link to large videos externally.
- Promotional links without process and verification evidence are not accepted.

## Pull Request checklist

- [ ] The change focuses on one subject.
- [ ] Relative links and image paths work.
- [ ] Version and environment details are included where relevant.
- [ ] Asset sources and permissions are disclosed.
- [ ] No secrets, private data, or large raw files are included.
- [ ] The case index, skill capability index, and both language versions are updated.

By participating, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md) and license your contribution under the repository license.
