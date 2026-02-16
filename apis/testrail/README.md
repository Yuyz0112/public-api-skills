# TestRail API

[TestRail API v2](https://support.testrail.com/hc/en-us/articles/7077083596436-Introduction-to-the-TestRail-API) in [Agent Skills](https://agentskills.io/) format.

**API Version:** `v2`

## Usage

Point your AI agent to read `testrail-api/SKILL.md` as the entry point.

## Structure

```
testrail-api/
├── SKILL.md                    # Entry point
└── references/
    ├── resources/
    ├── operations/
    ├── schemas/
    └── authentication.md
```

## Regenerate

```bash
bun run generate:testrail
bun run generate:testrail:readonly
```

## Source

- Canonical source list: [SOURCES.md](./SOURCES.md).

## Notes

- This OpenAPI spec is community-maintained and optimized for Agent Skills generation.
- TestRail-specific custom fields are represented with flexible schemas (`additionalProperties: true`).
- Official source links are tracked in `apis/testrail/SOURCES.md`.
- Operations are tagged with normalized access tags: `read` (GET) and `write` (POST).
- Generated skills are kept in the same directory:
  - `apis/testrail/testrail-api`
  - `apis/testrail/testrail-api-readonly`
