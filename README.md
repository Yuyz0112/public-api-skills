# Stripe API Skills

[Stripe API](https://stripe.com/docs/api) in [Agent Skills](https://agentskills.io/) format for AI agents.

## Usage

Point your AI agent to read `stripe-api/SKILL.md` as the entry point.

## Structure

```
stripe-api/
├── SKILL.md                    # Entry point
└── references/
    ├── resources/              # 77 resource files
    ├── operations/             # 588 operation files
    ├── schemas/                # 1315 schema files
    └── authentication.md
```

## Regenerate

To regenerate from the latest OpenAPI spec:

```bash
# Update openapi.json from Stripe
curl -o openapi.json https://raw.githubusercontent.com/stripe/openapi/master/openapi/spec3.json

# Regenerate skills
bun run generate
```

## License

The Stripe OpenAPI specification is owned by Stripe. This repository only provides a reformatted version for AI agent consumption.
