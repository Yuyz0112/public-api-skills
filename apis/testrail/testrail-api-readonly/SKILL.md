---
name: testrail-api-readonly
description: Community-maintained OpenAPI 3.0 specification for TestRail API v2.. Use when working with the TestRail API or when the user needs to interact with this API.
metadata:
  api-version: "0.1.0"
  openapi-version: "3.0.3"
---

# TestRail API

Community-maintained OpenAPI 3.0 specification for TestRail API v2.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 1 resource index files
├── operations/     # 24 operation detail files
└── schemas/        # 18 schema groups, 38 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://{instance}` - TestRail instance

## Authentication

Supported methods: **basicAuth**. See `references/authentication.md` for details.

## Resources

- **read** → `references/resources/read.md` (24 ops) - Read-only operations (typically GET)
