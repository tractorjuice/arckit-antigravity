---
name: arckit-aws-research
description: "Research AWS services and architecture patterns using AWS Knowledge MCP for authoritative guidance"
---

This command reads a great deal, so it runs in a subagent to keep that reading out of this conversation.

1. Start the `arckit-aws-research-agent` subagent, which comes with the ArcKit plugin. Give it the user's request word for word, the absolute path of this workspace, and the project the request is about if you know it.
2. Wait for it to finish. Then tell the user what it found and which files it wrote.

If you cannot start a subagent, read `instructions.md` in this skill's folder from its first line to its last, and follow it yourself.

## User Input

```text
$ARGUMENTS
```
