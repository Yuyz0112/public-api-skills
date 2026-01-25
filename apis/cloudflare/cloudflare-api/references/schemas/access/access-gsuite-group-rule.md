# access_gsuite_group_rule

Matches a group in Google Workspace.
Requires a Google Workspace identity provider.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gsuite` | object | Yes |  |

## Nested Fields

### `gsuite`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | string | Yes | The email of the Google Workspace group. |
| `identity_provider_id` | string | Yes | The ID of your Google Workspace identity provider. |

