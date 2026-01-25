# Stripe API

[Stripe API](https://stripe.com/docs/api) in [Agent Skills](https://agentskills.io/) format.

**API Version:** `2026-01-28.clover`

## Usage

Point your AI agent to read `stripe-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Source | 1 file (7.2 MB) | 2,135 files |
| Resources | - | 77 index files |
| Operations | 588 (all in one) | 588 individual files |
| Schemas | 1,315 (all in one) | 1,468 individual files |

## Structure

```
stripe-api/
├── SKILL.md                    # Entry point
└── references/
    ├── resources/              # 77 resource index files
    ├── operations/             # 588 operation detail files
    ├── schemas/                # 1,468 schema files
    └── authentication.md
```

## Regenerate

```bash
# Update openapi.json from Stripe
curl -o apis/stripe/openapi.json https://raw.githubusercontent.com/stripe/openapi/master/openapi/spec3.json

# Regenerate
bun run generate:stripe
```

## Source

- OpenAPI Spec: https://github.com/stripe/openapi
- API Docs: https://stripe.com/docs/api
