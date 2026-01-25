---
name: discord-http-api-preview
description: Preview of the Discord v10 HTTP API specification. See https://discord.com/developers/docs for more details.. Use when working with the Discord HTTP API (Preview) or when the user needs to interact with this API.
license: MIT
metadata:
  api-version: "10"
  openapi-version: "3.1.0"
---

# Discord HTTP API (Preview)

Preview of the Discord v10 HTTP API specification. See https://discord.com/developers/docs for more details.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 16 resource index files
├── operations/     # 227 operation detail files
└── schemas/        # 123 schema groups, 490 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://discord.com/api/v10`

## Authentication

Supported methods: **BotToken**, **OAuth2**. See `references/authentication.md` for details.

## Resources

- **guilds** → `references/resources/guilds.md` (82 ops)
- **channels** → `references/resources/channels.md` (47 ops)
- **applications** → `references/resources/applications.md` (33 ops)
- **webhooks** → `references/resources/webhooks.md` (15 ops)
- **lobbies** → `references/resources/lobbies.md` (13 ops)
- **users** → `references/resources/users.md` (12 ops)
- **invites** → `references/resources/invites.md` (5 ops)
- **oauth2** → `references/resources/oauth2.md` (4 ops)
- **partner-sdk** → `references/resources/partner-sdk.md` (4 ops)
- **stage-instances** → `references/resources/stage-instances.md` (4 ops)
- **gateway** → `references/resources/gateway.md` (2 ops)
- **sticker-packs** → `references/resources/sticker-packs.md` (2 ops)
- **interactions** → `references/resources/interactions.md` (1 ops)
- **soundboard-default-sounds** → `references/resources/soundboard-default-sounds.md` (1 ops)
- **stickers** → `references/resources/stickers.md` (1 ops)
- **voice** → `references/resources/voice.md` (1 ops)
