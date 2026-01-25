# IssueEntityPropertiesForMultiUpdate

An issue ID with entity property values. See [Entity properties](https://developer.atlassian.com/cloud/jira/platform/jira-entity-properties/) for more information.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueID` | integer (int64) | No | The ID of the issue. |
| `properties` | object | No | Entity properties to set on the issue. The maximum length of an issue property value is 32768 characters. |

