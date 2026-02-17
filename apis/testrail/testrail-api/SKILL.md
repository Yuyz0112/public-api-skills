---
name: testrail-api
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
├── resources/      # 12 resource index files
├── operations/     # 43 operation detail files
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

- **attachments** → `references/resources/attachments.md` (9 ops)
- **results** → `references/resources/results.md` (6 ops)
- **cases** → `references/resources/cases.md` (5 ops)
- **runs** → `references/resources/runs.md` (5 ops)
- **plans** → `references/resources/plans.md` (4 ops)
- **users** → `references/resources/users.md` (3 ops)
- **projects** → `references/resources/projects.md` (2 ops)
- **suites** → `references/resources/suites.md` (2 ops)
- **sections** → `references/resources/sections.md` (2 ops)
- **tests** → `references/resources/tests.md` (2 ops)
- **milestones** → `references/resources/milestones.md` (2 ops)
- **statuses** → `references/resources/statuses.md` (1 ops)
