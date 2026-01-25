# JExpEvaluateIssuesJqlMetaDataBean

The description of the page of issues loaded by the provided JQL query.This bean will be replacing IssuesJqlMetaDataBean bean as part of new `evaluate` endpoint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isLast` | boolean | No | Indicates whether this is the last page of the paginated response. |
| `nextPageToken` | string | Yes | Next Page token for the next page of issues. |

