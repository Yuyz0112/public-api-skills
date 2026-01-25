# SearchAndReconcileResults

The result of a JQL search with issues reconsilation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isLast` | boolean | No | Indicates whether this is the last page of the paginated response. |
| `issues` | IssueBean[] | No | The list of issues found by the search or reconsiliation. |
| `names` | object | No | The ID and name of each field in the search results. |
| `nextPageToken` | string | No | Continuation token to fetch the next page. If this result represents the last or the only page this token will be null. This token will expire in 7 days. |
| `schema` | object | No | The schema describing the field types in the search results. |

