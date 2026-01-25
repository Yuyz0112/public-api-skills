# access_azure_group_rule

Matches an Azure group.
Requires an Azure identity provider.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `azureAD` | object | Yes |  |

## Nested Fields

### `azureAD`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID of an Azure group. |
| `identity_provider_id` | string | Yes | The ID of your Azure identity provider. |

