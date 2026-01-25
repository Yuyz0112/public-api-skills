# RemoveOptionFromIssuesResult

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | any | No | A collection of errors related to unchanged issues. The collection size is limited, which means not all errors may be returned. |
| `modifiedIssues` | integer[] | No | The IDs of the modified issues. |
| `unmodifiedIssues` | integer[] | No | The IDs of the unchanged issues, those issues where errors prevent modification. |

