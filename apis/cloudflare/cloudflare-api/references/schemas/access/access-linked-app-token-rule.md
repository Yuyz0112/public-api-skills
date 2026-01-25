# access_linked_app_token_rule

Matches OAuth 2.0 access tokens issued by the specified Access OIDC SaaS application. Only compatible with non_identity and bypass decisions.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `linked_app_token` | object | Yes |  |

## Nested Fields

### `linked_app_token`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `app_uid` | string | Yes | The ID of an Access OIDC SaaS application |

