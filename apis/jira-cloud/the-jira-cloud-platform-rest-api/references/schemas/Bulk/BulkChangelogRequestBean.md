# BulkChangelogRequestBean

Request bean for bulk changelog retrieval

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fieldIds` | string[] | No | List of field IDs to filter changelogs |
| `issueIdsOrKeys` | string[] | Yes | List of issue IDs/keys to fetch changelogs for |
| `maxResults` | integer (int32) | No | The maximum number of items to return per page |
| `nextPageToken` | string | No | The cursor for pagination |

