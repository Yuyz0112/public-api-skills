# Discord API

[Discord HTTP API](https://discord.com/developers/docs/intro) in [Agent Skills](https://agentskills.io/) format.

## Usage

Point your AI agent to read `discord-http-api-preview/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Operations | 227 | 227 individual files |
| Schemas | 490 | 490 individual files |

## Regenerate

```bash
curl -o apis/discord/openapi.json "https://raw.githubusercontent.com/discord/discord-api-spec/main/specs/openapi.json"
bun run generate:discord
```

## Source

- OpenAPI Spec: https://github.com/discord/discord-api-spec
- API Docs: https://discord.com/developers/docs/intro
