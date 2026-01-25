# GET /2/activity/stream

**Resource:** [Activity](../resources/Activity.md)
**Activity Stream**
**Operation ID:** `activityStream`

Stream of X Activities

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `backfill_minutes` | query | integer (int32) | No | The number of minutes of backfill requested. |
| `start_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The earliest UTC timestamp from which the Post labels will be provided. |
| `end_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The latest UTC timestamp from which the Post labels will be provided. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ActivityStreamingResponse](../schemas/Activity/ActivityStreamingResponse.md)

## Security

- **BearerToken**
