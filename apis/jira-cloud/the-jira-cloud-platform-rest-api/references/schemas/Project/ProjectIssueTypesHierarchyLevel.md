# ProjectIssueTypesHierarchyLevel

Details of an issue type hierarchy level.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `entityId` | string (uuid) | No | The ID of the issue type hierarchy level. This property is deprecated, see [Change notice: Removing hierarchy level IDs from next-gen APIs](https://developer.atlassian.com/cloud/jira/platform/change-notice-removing-hierarchy-level-ids-from-next-gen-apis/). |
| `issueTypes` | IssueTypeInfo[] | No | The list of issue types in the hierarchy level. |
| `level` | integer (int32) | No | The level of the issue type hierarchy level. |
| `name` | string | No | The name of the issue type hierarchy level. |

