# PageOfStatuses

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isLast` | boolean | No | Whether this is the last page. |
| `maxResults` | integer (int32) | No | The maximum number of items that could be returned. |
| `nextPage` | string | No | The URL of the next page of results, if any. |
| `self` | string | No | The URL of this page. |
| `startAt` | integer (int64) | No | The index of the first item returned on the page. |
| `total` | integer (int64) | No | Number of items that satisfy the search. |
| `values` | JiraStatus[] | No | The list of items. |

