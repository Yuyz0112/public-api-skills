# CreateExclusionRulesRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueIds` | integer[] | No | The IDs of the issues to exclude from the plan. |
| `issueTypeIds` | integer[] | No | The IDs of the issue types to exclude from the plan. |
| `numberOfDaysToShowCompletedIssues` | integer (int32) | No | Issues completed this number of days ago will be excluded from the plan. |
| `releaseIds` | integer[] | No | The IDs of the releases to exclude from the plan. |
| `workStatusCategoryIds` | integer[] | No | The IDs of the work status categories to exclude from the plan. |
| `workStatusIds` | integer[] | No | The IDs of the work statuses to exclude from the plan. |

