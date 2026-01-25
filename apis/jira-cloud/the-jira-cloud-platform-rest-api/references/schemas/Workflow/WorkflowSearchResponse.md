# WorkflowSearchResponse

Page of items, including workflows and related statuses.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isLast` | boolean | No | Whether this is the last page. |
| `maxResults` | integer (int32) | No | The maximum number of items that could be returned. |
| `nextPage` | string | No | If there is another page of results, the URL of the next page. |
| `self` | string | No | The URL of the page. |
| `startAt` | integer (int64) | No | The index of the first item returned. |
| `statuses` | JiraWorkflowStatus[] | No | List of statuses. |
| `total` | integer (int64) | No | The number of items returned. |
| `values` | JiraWorkflow[] | No | List of workflows. |

