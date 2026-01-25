# FieldConfigurationIssueTypeItem

The field configuration for an issue type.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fieldConfigurationId` | string | Yes | The ID of the field configuration. |
| `fieldConfigurationSchemeId` | string | Yes | The ID of the field configuration scheme. |
| `issueTypeId` | string | Yes | The ID of the issue type or *default*. When set to *default* this field configuration issue type item applies to all issue types without a field configuration. |

