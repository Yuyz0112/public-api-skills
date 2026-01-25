# IssuesJqlMetaDataBean

The description of the page of issues loaded by the provided JQL query.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer (int32) | Yes | The number of issues that were loaded in this evaluation. |
| `maxResults` | integer (int32) | Yes | The maximum number of issues that could be loaded in this evaluation. |
| `startAt` | integer (int64) | Yes | The index of the first issue. |
| `totalCount` | integer (int64) | Yes | The total number of issues the JQL returned. |
| `validationWarnings` | string[] | No | Any warnings related to the JQL query. Present only if the validation mode was set to `warn`. |

