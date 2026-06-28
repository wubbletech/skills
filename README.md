# Wubble Skills

Public AI-agent skills for Wubble.

## Available Skills

### Wubble

Location:

```text
skills/wubble/SKILL.md
```

Use this skill when an agent or user wants to connect to Wubble's official
remote MCP server for music, speech, voice, dubbing, and sound-effect
workflows.

Official MCP Registry name:

```text
ai.wubble/audio
```

Remote MCP endpoint:

```text
https://mcp.wubble.ai/mcp
```

ClawHub package:

```text
wubble@1.0.1
```

## Install

Install the Wubble skill with the Skills CLI:

```bash
npx skills add wubbletech/skills --skill wubble
```

Or install directly from GitHub:

```bash
npx skills add https://github.com/wubbletech/skills/tree/main/skills/wubble
```

## skills.sh

After this repository is public and indexed, the expected listing is:

```text
https://skills.sh/wubbletech/skills/wubble
```

## Security

The Wubble MCP server uses OAuth for protected tool calls. Do not ask users for
Wubble API keys or secrets when a client-provided OAuth flow is available.

Some Wubble tools create media, upload user media, remix assets, dub voices, or
otherwise consume Wubble requests or credits. Agents should confirm user intent
before starting generation or spendful actions.

Do not log, store, or reveal OAuth tokens, Wubble API keys, signed media URLs,
or private user media.

## Legal

Use of Wubble is governed by Wubble's official Terms of Use and Subscriber
License:

- [Terms of Use](TERMS.md)
- [Subscriber License](LICENSE)

Current public legal pages:

- https://wubble.ai/docs/legal/terms
- https://wubble.ai/docs/legal/license
