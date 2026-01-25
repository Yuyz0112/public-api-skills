# BulkOperationProgress

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | string (date-time) | No | A timestamp of when the task was submitted. |
| `failedAccessibleIssues` | object | No | Map of issue IDs for which the operation failed and that the user has permission to view, to their one or more reasons for failure. These reasons are open-ended text descriptions of the error and are not selected from a predefined list of standard reasons. |
| `invalidOrInaccessibleIssueCount` | integer (int32) | No | The number of issues that are either invalid or issues that the user doesn't have permission to view, regardless of the success or failure of the operation. |
| `processedAccessibleIssues` | integer[] | No | List of issue IDs for which the operation was successful and that the user has permission to view. |
| `progressPercent` | integer (int64) | No | Progress of the task as a percentage. |
| `started` | string (date-time) | No | A timestamp of when the task was started. |
| `status` | enum: ENQUEUED, RUNNING, COMPLETE... | No | The status of the task. |
| `submittedBy` | [User](User.md) | No |  |
| `taskId` | string | No | The ID of the task. |
| `totalIssueCount` | integer (int32) | No | The number of issues that the bulk operation was attempted on. |
| `updated` | string (date-time) | No | A timestamp of when the task progress was last updated. |

