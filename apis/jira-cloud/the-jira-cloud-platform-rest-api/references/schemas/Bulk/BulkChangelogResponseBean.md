# BulkChangelogResponseBean

A page of changelogs which is designed to handle multiple issues

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueChangeLogs` | IssueChangeLog[] | No | The list of issues changelogs. |
| `nextPageToken` | string | No | Continuation token to fetch the next page. If this result represents the last or the only page, this token will be null. |

