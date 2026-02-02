# POST /reindex/issue

**Resource:** [reindex](../resources/reindex.md)
**Operation ID:** `reindexIssues`

Reindexes one or more individual issues.  Indexing is performed synchronously - the call returns when indexing of
 the issues has completed or a failure occurs.
 <p>
 Use either explicitly specified issue IDs or a JQL query to select issues to reindex.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueId` | query | string | No | the IDs or keys of one or more issues to reindex. |
| `indexComments` | query | boolean | No | Indicates that comments should also be reindexed. |
| `indexChangeHistory` | query | boolean | No | Indicates that changeHistory should also be reindexed. |
| `indexWorklogs` | query | boolean | No | Indicates that changeHistory should also be reindexed. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

