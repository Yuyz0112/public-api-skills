---
name: figma-api
description: This is the OpenAPI specification for the [Figma REST API](https://www.figma.com/developers/api).. Use when working with the Figma API or when the user needs to interact with this API.
metadata:
  api-version: "0.36.0"
  openapi-version: "3.1.0"
  contact: "support@figma.com"
---

# Figma API

This is the OpenAPI specification for the [Figma REST API](https://www.figma.com/developers/api).

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 14 resource index files
├── operations/     # 46 operation detail files
└── schemas/        # 105 schema groups, 223 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://api.figma.com`

## Authentication

Supported methods: **PersonalAccessToken**, **OAuth2**, **OrgOAuth2**. See `references/authentication.md` for details.

## Resources

- **Webhooks** → `references/resources/Webhooks.md` (7 ops) - Interact with team webhooks as a team admin.
- **Files** → `references/resources/Files.md` (6 ops) - Get file JSON, images, and other file-related cont
- **Library Analytics** → `references/resources/Library-Analytics.md` (6 ops) - Get analytics data for your published libraries.
- **Dev Resources** → `references/resources/Dev-Resources.md` (4 ops) - Interact with dev resources in Figma Dev Mode.
- **Comments** → `references/resources/Comments.md` (3 ops) - Interact with file comments.
- **Comment Reactions** → `references/resources/Comment-Reactions.md` (3 ops) - Interact with reactions to file comments.
- **Components** → `references/resources/Components.md` (3 ops) - Get information about published components.
- **Component Sets** → `references/resources/Component-Sets.md` (3 ops) - Get information about published component sets.
- **Styles** → `references/resources/Styles.md` (3 ops) - Get information about published styles.
- **Variables** → `references/resources/Variables.md` (3 ops) - Interact with variables in an Enterprise organizat
- **Projects** → `references/resources/Projects.md` (2 ops) - Get information about projects and files in teams.
- **Users** → `references/resources/Users.md` (1 ops) - Get information about the currently authenticated 
- **Activity Logs** → `references/resources/Activity-Logs.md` (1 ops) - Get activity logs as an organization admin.
- **Payments** → `references/resources/Payments.md` (1 ops) - Get purchase information for your Community resour
