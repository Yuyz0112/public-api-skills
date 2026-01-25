# webhook-custom-property-values-updated

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: updated | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | No |  |
| `new_property_values` | custom-property-value[] | Yes | The new custom property values for the repository. |
| `old_property_values` | custom-property-value[] | Yes | The old custom property values for the repository. |

