# access_github_organization_rule

Matches a Github organization.
Requires a Github identity provider.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `github-organization` | object | Yes |  |

## Nested Fields

### `github-organization`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `identity_provider_id` | string | Yes | The ID of your Github identity provider. |
| `name` | string | Yes | The name of the organization. |
| `team` | string | No | The name of the team |

