# WeChat Fact Checking Context

## Scope

Check factual and technical accuracy in WeChat articles, especially content about:

- computer concepts
- AI Coding
- APIs
- databases
- cloud services
- deployment
- servers
- GitHub
- Supabase
- Coze / 扣子
- WeChat Reading Skill or other platform-specific capabilities
- email protocols such as POP3 / IMAP
- financial markets, investment, taxation, regulation, or economic claims

## Verification standard

When facts may be current, platform-specific, technical, legal, financial, regulatory, or otherwise time-sensitive, require verification from authoritative or official sources.

## Output risk categories

- Low: wording is broadly accurate and no source is needed for general conceptual statements.
- Medium: statement is probably right but needs qualification, source, or clearer wording.
- High: statement may be false, outdated, misleading, exaggerated, or legally/financially sensitive.

## Common issues to flag

- Treating AI Coding as if it eliminates all engineering complexity.
- Overstating platform capabilities.
- Describing unofficial or brittle workarounds as stable official capabilities.
- Confusing API, webhook, connector, MCP, and Skill.
- Confusing frontend, backend, database, server, cloud service, and deployment.
- Making financial or investment claims without sources.
- Making legal, regulatory, tax, or compliance claims without authoritative sources.

## Preferred correction style

Use precise, qualified wording:

- “更准确地说……”
- “这里需要区分……”
- “这个表述可以保留，但建议补充限制条件……”
- “这个事实需要用官方文档或权威来源确认。”
