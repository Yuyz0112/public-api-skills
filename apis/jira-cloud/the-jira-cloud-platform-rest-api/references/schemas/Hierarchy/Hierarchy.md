# Hierarchy

The project issue type hierarchy.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `baseLevelId` | integer (int64) | No | The ID of the base level. This property is deprecated, see [Change notice: Removing hierarchy level IDs from next-gen APIs](https://developer.atlassian.com/cloud/jira/platform/change-notice-removing-hierarchy-level-ids-from-next-gen-apis/). |
| `levels` | SimplifiedHierarchyLevel[] | No | Details about the hierarchy level. |

