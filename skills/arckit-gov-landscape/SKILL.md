---
name: arckit-gov-landscape
description: "Map the UK government code landscape for a domain — who built what, common patterns, standards, maturity"
---

This command reads a great deal, so it runs in a subagent to keep that reading out of this conversation.

1. Start the `arckit-gov-landscape-agent` subagent, which comes with the ArcKit plugin. Give it the user's request word for word, the absolute path of this workspace, and the project the request is about if you know it.
2. Wait for it to finish. Then tell the user what it found and which files it wrote.

If you cannot start a subagent, read `instructions.md` in this skill's folder from its first line to its last, and follow it yourself.

## User Input

```text
$ARGUMENTS
```
