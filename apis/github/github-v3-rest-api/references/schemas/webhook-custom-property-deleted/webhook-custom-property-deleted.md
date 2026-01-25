# webhook-custom-property-deleted

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: deleted | Yes |  |
| `definition` | object | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `definition`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `property_name` | string | Yes | The name of the property that was deleted. |

