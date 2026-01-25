# access_auth_context_rule

Matches an Azure Authentication Context.
Requires an Azure identity provider.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auth_context` | object | Yes |  |

## Nested Fields

### `auth_context`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ac_id` | string | Yes | The ACID of an Authentication context. |
| `id` | string | Yes | The ID of an Authentication context. |
| `identity_provider_id` | string | Yes | The ID of your Azure identity provider. |

