# BulkIssuePropertyUpdateRequest

Bulk issue property update request details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expression` | string | No | EXPERIMENTAL. The Jira expression to calculate the value of the property. The value of the expression must be an object that can be converted to JSON, such as a number, boolean, string, list, or map. The context variables available to the expression are `issue` and `user`. Issues for which the expression returns a value whose JSON representation is longer than 32768 characters are ignored. |
| `filter` | any | No | The bulk operation filter. |
| `value` | any | No | The value of the property. The value must be a [valid](https://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters. |

