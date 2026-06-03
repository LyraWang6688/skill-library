---
name: wechat-html-css-layout
description: generate brand-consistent html and inline css layouts for 要AI不释手 wechat official account articles. use when the user asks for公众号排版, html+css, 壹伴可复制排版, brand style layout, mobile-friendly article formatting, summary modules, quote cards, method cards, image modules, or fixed column ending image insertion.
---

# WeChat HTML/CSS Layout

Generate WeChat-compatible HTML with inline CSS using the 要AI不释手 brand system.

## Rules

- Use inline CSS only.
- Use stable `section + p` structures.
- Avoid unnecessary complex nesting.
- Prefer card-style comparison blocks over tables for rendering stability.
- Use the fixed color system exactly.
- Keep mobile reading comfortable.
- Insert the fixed column ending image placeholder when the real URL is not available.
- Do not generate a fixed text ending by default; use the column ending image module.

## Required modules

When relevant, include:

1. Reading info.
2. Content summary module.
3. Body paragraphs.
4. Section headings.
5. Quote / core idea modules.
6. Method / checklist modules.
7. Normal information cards.
8. Image modules.
9. Column ending image module.

## Output format

1. `# 使用说明`
2. `# HTML + inline CSS`
3. `# 占位符说明`

## References

- `references/wechat-layout-context.md`
- `references/wechat-html-template.md`
- `references/ending-image-rules.md`
