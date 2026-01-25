# access_okta_group_rule

Matches an Okta group.
Requires an Okta identity provider.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `okta` | object | Yes |  |

## Nested Fields

### `okta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `identity_provider_id` | string | Yes | The ID of your Okta identity provider. |
| `name` | string | Yes | The name of the Okta group. |

