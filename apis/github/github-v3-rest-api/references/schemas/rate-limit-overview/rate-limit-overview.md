# rate-limit-overview

Rate Limit Overview

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resources` | object | Yes |  |
| `rate` | [rate-limit](rate-limit.md) | Yes |  |

## Nested Fields

### `resources`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `core` | [rate-limit](rate-limit.md) | Yes |  |
| `graphql` | [rate-limit](rate-limit.md) | No |  |
| `search` | [rate-limit](rate-limit.md) | Yes |  |
| `code_search` | [rate-limit](rate-limit.md) | No |  |
| `source_import` | [rate-limit](rate-limit.md) | No |  |
| `integration_manifest` | [rate-limit](rate-limit.md) | No |  |
| `code_scanning_upload` | [rate-limit](rate-limit.md) | No |  |
| `actions_runner_registration` | [rate-limit](rate-limit.md) | No |  |
| `scim` | [rate-limit](rate-limit.md) | No |  |
| `dependency_snapshots` | [rate-limit](rate-limit.md) | No |  |
| `dependency_sbom` | [rate-limit](rate-limit.md) | No |  |
| `code_scanning_autofix` | [rate-limit](rate-limit.md) | No |  |

