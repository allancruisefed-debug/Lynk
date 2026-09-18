---
name: lynk-master
description: Multi-action Edge Gallery skill with web search, memory, and context loading.
---

# Lynk Master Skill

Actions:
- `search` — search the web.
- `memory` — save, get, search, or delete local memory.
- `context` — load the persona and extra system prompt.

## Execution
Use the Edge Gallery JavaScript runner with:
`scripts/index.html`

Pass JSON through `run_js`.

Examples:
- `{"action":"search","query":"your query"}`
- `{"action":"memory","operation":"save","key":"name","value":"Allan"}`
- `{"action":"memory","operation":"get","key":"name"}`
- `{"action":"memory","operation":"search","query":"name"}`
- `{"action":"memory","operation":"delete","key":"name"}`
- `{"action":"context"}`

Memory is stored locally by this skill.

## Rules
- Use only the exact actions: `search`, `memory`, `context`.
- Report actual errors; never invent results.
