# SimplifiedHierarchyLevel

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `aboveLevelId` | integer (int64) | No | The ID of the level above this one in the hierarchy. This property is deprecated, see [Change notice: Removing hierarchy level IDs from next-gen APIs](https://developer.atlassian.com/cloud/jira/platform/change-notice-removing-hierarchy-level-ids-from-next-gen-apis/). |
| `belowLevelId` | integer (int64) | No | The ID of the level below this one in the hierarchy. This property is deprecated, see [Change notice: Removing hierarchy level IDs from next-gen APIs](https://developer.atlassian.com/cloud/jira/platform/change-notice-removing-hierarchy-level-ids-from-next-gen-apis/). |
| `externalUuid` | string (uuid) | No | The external UUID of the hierarchy level. This property is deprecated, see [Change notice: Removing hierarchy level IDs from next-gen APIs](https://developer.atlassian.com/cloud/jira/platform/change-notice-removing-hierarchy-level-ids-from-next-gen-apis/). |
| `hierarchyLevelNumber` | integer (int32) | No |  |
| `id` | integer (int64) | No | The ID of the hierarchy level. This property is deprecated, see [Change notice: Removing hierarchy level IDs from next-gen APIs](https://developer.atlassian.com/cloud/jira/platform/change-notice-removing-hierarchy-level-ids-from-next-gen-apis/). |
| `issueTypeIds` | integer[] | No | The issue types available in this hierarchy level. |
| `level` | integer (int32) | No | The level of this item in the hierarchy. |
| `name` | string | No | The name of this hierarchy level. |
| `projectConfigurationId` | integer (int64) | No | The ID of the project configuration. This property is deprecated, see [Change oticen: Removing hierarchy level IDs from next-gen APIs](https://developer.atlassian.com/cloud/jira/platform/change-notice-removing-hierarchy-level-ids-from-next-gen-apis/). |

