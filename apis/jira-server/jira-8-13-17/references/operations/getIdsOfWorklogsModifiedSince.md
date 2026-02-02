# GET /worklog/updated

**Resource:** [worklog](../resources/worklog.md)
**Operation ID:** `getIdsOfWorklogsModifiedSince`

Returns worklogs id and update time of worklogs that was updated since given time.
 The returns set of worklogs is limited to 1000 elements.
 This API will not return worklogs updated during last minute.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `since` | query | integer (int64) | No | a date time in unix timestamp format since when updated worklogs will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

