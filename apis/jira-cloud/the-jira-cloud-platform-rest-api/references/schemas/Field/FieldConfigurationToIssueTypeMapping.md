# FieldConfigurationToIssueTypeMapping

The field configuration to issue type mapping.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fieldConfigurationId` | string | Yes | The ID of the field configuration. |
| `issueTypeId` | string | Yes | The ID of the issue type or *default*. When set to *default* this field configuration issue type item applies to all issue types without a field configuration. An issue type can be included only once in a request. |

