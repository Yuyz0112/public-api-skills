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
| [GitHub](./apis/github/) | 1,078 | 904 | `apis/github/` |
| [Stripe](./apis/stripe/) | 588 | 1,315 | `apis/stripe/` |

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
