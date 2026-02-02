# POST /reindex

**Resource:** [reindex](../resources/reindex.md)
**Operation ID:** `reindex`

Kicks off a reindex.  Need Admin permissions to perform this reindex.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | query | string | No | Case insensitive String indicating type of reindex.  If omitted, then defaults to BACKGROUND_PREFERRED. |
| `indexComments` | query | boolean | No | Indicates that comments should also be reindexed. Not relevant for foreground reindex, where comments are always reindexed. |
| `indexChangeHistory` | query | boolean | No | Indicates that changeHistory should also be reindexed. Not relevant for foreground reindex, where changeHistory is always reindexed. |
| `indexWorklogs` | query | boolean | No | Indicates that changeHistory should also be reindexed. Not relevant for foreground reindex, where changeHistory is always reindexed. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

