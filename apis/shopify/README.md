# Shopify API

[Shopify Admin API](https://shopify.dev/docs/api/admin-rest) in [Agent Skills](https://agentskills.io/) format.

## Usage

Point your AI agent to read `shopify-admin-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Operations | 4,567 | 4,567 individual files |
| Schemas | - | - |

## Regenerate

```bash
curl -o apis/shopify/openapi.json "https://raw.githubusercontent.com/allengrant/shopify_openapi/master/shopify_openapi.json"
bun run generate:shopify
```

## Source

- OpenAPI Spec: https://github.com/allengrant/shopify_openapi (community)
- API Docs: https://shopify.dev/docs/api/admin-rest
