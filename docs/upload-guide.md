# Upload Guide

## How to upload a Skill to ChatGPT

1. Download the target `.zip` package from `dist/`.
2. Open ChatGPT Skills.
3. Upload one Skill zip at a time.
4. Test the Skill with a simple trigger phrase.

## Important notes

- Upload each Skill zip individually.
- Do not upload a collection zip that contains multiple Skill zips.
- If an upload fails, inspect the Skill's `SKILL.md` and package structure.
- Keep each Skill package under the supported upload size limit.

## Recommended test flow

After upload, run a simple task:

```text
调用 wechat-title-generator，基于这篇文章生成 10 个公众号标题。
```
