---
name: x-api-v2
description: X API v2 available endpoints. Use when working with the X API v2 or when the user needs to interact with this API.
license: X Developer Agreement and Policy (https://developer.x.com/en/developer-terms/agreement-and-policy.html)
metadata:
  api-version: "2.157"
  openapi-version: "3.0.0"
---

# X API v2

X API v2 available endpoints

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 20 resource index files
├── operations/     # 192 operation detail files
└── schemas/        # 111 schema groups, 393 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://api.x.com` - X API

## Authentication

Supported methods: **BearerToken**, **OAuth2UserToken**, **UserToken**. See `references/authentication.md` for details.

## Resources

- **Users** → `references/resources/Users.md` (42 ops) - Endpoints related to retrieving, managing relation
- **Tweets** → `references/resources/Tweets.md` (38 ops) - Endpoints related to retrieving, searching, and mo
- **Stream** → `references/resources/Stream.md` (22 ops) - Endpoints related to streaming
- **Lists** → `references/resources/Lists.md` (17 ops) - Endpoints related to retrieving, managing Lists
- **Media** → `references/resources/Media.md` (11 ops) - Endpoints related to Media
- **Direct Messages** → `references/resources/Direct-Messages.md` (8 ops) - Endpoints related to retrieving, managing Direct M
- **Webhooks** → `references/resources/Webhooks.md` (8 ops)
- **Compliance** → `references/resources/Compliance.md` (7 ops) - Endpoints related to keeping X data in your system
- **Account Activity** → `references/resources/Account-Activity.md` (6 ops) - Endpoints relating to retrieving, managing AAA sub
- **Spaces** → `references/resources/Spaces.md` (6 ops) - Endpoints related to retrieving, managing Spaces
- **Activity** → `references/resources/Activity.md` (5 ops)
- **Community Notes** → `references/resources/Community-Notes.md` (5 ops)
- **Bookmarks** → `references/resources/Bookmarks.md` (5 ops) - Endpoints related to retrieving, managing bookmark
- **Communities** → `references/resources/Communities.md` (2 ops)
- **Connections** → `references/resources/Connections.md` (2 ops) - Endpoints related to streaming connections
- **Likes** → `references/resources/Likes.md` (2 ops)
- **News** → `references/resources/News.md` (2 ops) - Endpoint for retrieving news stories
- **Trends** → `references/resources/Trends.md` (2 ops)
- **General** → `references/resources/General.md` (1 ops) - Miscellaneous endpoints for general API functional
- **Usage** → `references/resources/Usage.md` (1 ops)
