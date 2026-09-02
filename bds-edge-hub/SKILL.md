---
name: bds-edge-hub
description: Test the Google AI Edge Gallery JavaScript execution environment.
---

## how to use this skill
When you need to perform any action, call the `run_js` tool with these **exact** parameters:

- **scriptName**: `scripts/index.html`
- **data**: A JSON string with this structure:

{"action":"test"}

# Edge Test

Use the `run_js` tool.

Pass the data as a JSON string.

For testing, call the tool with:

{"action":"test"}

Report the returned result exactly.
