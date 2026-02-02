# GET /worklog/deleted

**Resource:** [worklog](../resources/worklog.md)
**Operation ID:** `getIdsOfWorklogsDeletedSince`

Returns worklogs id and delete time of worklogs that was deleted since given time.
 The returns set of worklogs is limited to 1000 elements.
 This API will not return worklogs deleted during last minute.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `since` | query | integer (int64) | No | a date time in unix timestamp format since when deleted worklogs will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

