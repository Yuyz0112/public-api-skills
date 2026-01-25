# MandatoryFieldValueForADF

An object notation input

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `retain` | boolean | No | If `true`, will try to retain original non-null issue field values on move. |
| `type` | enum: adf, raw | Yes | Will treat as `MandatoryFieldValueForADF` if type is `adf` |
| `value` | object | Yes | Value for each field. Accepts Atlassian Document Format (ADF) for rich text fields like `description`, `environments`. For ADF format details, refer to: [Atlassian Document Format](https://developer.atlassian.com/cloud/jira/platform/apis/document/structure) |

