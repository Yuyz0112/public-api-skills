# GET /reindex

**Resource:** [reindex](../resources/reindex.md)
**Operation ID:** `getReindexInfo`

Returns information on the system reindexes.  If a reindex is currently taking place then information about this reindex is returned.
 If there is no active index task, then returns information about the latest reindex task run, otherwise returns a 404
 indicating that no reindex has taken place.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | query | integer (int64) | No | the id of an indexing task you wish to obtain details on.  If omitted, then defaults to the standard behaviour and
               returns information on the active reindex task, or the last task to run if no reindex is taking place. .  If there is no
               reindexing task with that id then a 404 is returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

