# IssueFieldOption

Details of the options for a select list issue field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config` | [IssueFieldOptionConfiguration](IssueFieldOptionConfiguration.md) | No |  |
| `id` | integer (int64) | Yes | The unique identifier for the option. This is only unique within the select field's set of options. |
| `properties` | object | No | The properties of the object, as arbitrary key-value pairs. These properties can be searched using JQL, if the extractions (see [Issue Field Option Property Index](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field-option-property-index/)) are defined in the descriptor for the issue field module. |
| `value` | string | Yes | The option's name, which is displayed in Jira. |

