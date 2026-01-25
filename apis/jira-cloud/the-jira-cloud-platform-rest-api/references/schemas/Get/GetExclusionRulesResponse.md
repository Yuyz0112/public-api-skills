# GetExclusionRulesResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueIds` | integer[] | No | The IDs of the issues excluded from the plan. |
| `issueTypeIds` | integer[] | No | The IDs of the issue types excluded from the plan. |
| `numberOfDaysToShowCompletedIssues` | integer (int32) | Yes | Issues completed this number of days ago are excluded from the plan. |
| `releaseIds` | integer[] | No | The IDs of the releases excluded from the plan. |
| `workStatusCategoryIds` | integer[] | No | The IDs of the work status categories excluded from the plan. |
| `workStatusIds` | integer[] | No | The IDs of the work statuses excluded from the plan. |

