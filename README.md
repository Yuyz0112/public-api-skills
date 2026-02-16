# Public API Skills

A collection of public API documentation converted to [Agent Skills](https://agentskills.io/) format - structured markdown optimized for AI agents.

## Why Agent Skills?

AI agents often need to interact with external APIs. Raw OpenAPI specifications have limitations:

- **Too large** - Complex specs can be megabytes, exceeding LLM context limits
- **Wasteful** - Loading the entire document for every request wastes context
- **Monolithic** - All-or-nothing access prevents selective loading

Agent Skills solves this by splitting documentation into on-demand files. Agents load only what they need - start with an overview, drill into specific operations.

**No special integrations required.** File reading works in every agent framework.

## Available APIs

| API | Operations | Schemas | Directory |
|-----|------------|---------|-----------|
| [Asana](./apis/asana/) | 217 | 244 | `apis/asana/` |
| [Cloudflare](./apis/cloudflare/) | 2,531 | 5,231 | `apis/cloudflare/` |
| [Discord](./apis/discord/) | 227 | 490 | `apis/discord/` |
| [Figma](./apis/figma/) | 46 | 223 | `apis/figma/` |
| [GitLab](./apis/gitlab/) | 1,837 | 454 | `apis/gitlab/` |
| [GitHub](./apis/github/) | 1,078 | 904 | `apis/github/` |
| [Jira Cloud](./apis/jira-cloud/) | 616 | 967 | `apis/jira-cloud/` |
| [PagerDuty](./apis/pagerduty/) | 390 | 244 | `apis/pagerduty/` |
| [Shopify](./apis/shopify/) | 4,567 | - | `apis/shopify/` |
| [Slack](./apis/slack/) | 253 | 48 | `apis/slack/` |
| [Stripe](./apis/stripe/) | 588 | 1,315 | `apis/stripe/` |
| [TestRail](./apis/testrail/) | 40 | 36 | `apis/testrail/` |
| [Twilio](./apis/twilio/) | 197 | 148 | `apis/twilio/` |
| [Twitter/X](./apis/twitter/) | 192 | 393 | `apis/twitter/` |

## Usage

Point your AI agent to read `apis/<api-name>/<skill-name>/SKILL.md` as the entry point.

Example for Stripe:
```
apis/stripe/stripe-api/SKILL.md
```

## How It Works

Each API is converted using [openapi-to-skills](https://github.com/neutree-ai/openapi-to-skills):

```bash
npx openapi-to-skills ./openapi.json -o ./output
```

The tool transforms monolithic OpenAPI specs into a navigable file structure:

```
<skill-name>/
├── SKILL.md                    # Entry point with overview
└── references/
    ├── resources/              # One file per resource/tag
    ├── operations/             # One file per operation
    ├── schemas/                # Grouped schema files
    └── authentication.md
```

## Contributing

Want to add an API? Requirements:

1. Public API with an OpenAPI 3.x specification
2. Permissive license allowing redistribution of documentation

To add:

```bash
# Create directory
mkdir -p apis/<api-name>

# Download OpenAPI spec
curl -o apis/<api-name>/openapi.json <spec-url>

# Generate skills
bunx openapi-to-skills apis/<api-name>/openapi.json -o apis/<api-name>

# Add README and update this file
```

## License

Each API's documentation retains its original license. See individual API directories for details.

This repository structure and tooling is Apache-2.0.
