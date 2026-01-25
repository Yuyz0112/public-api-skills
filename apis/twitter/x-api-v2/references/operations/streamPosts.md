# GET /2/tweets/search/stream

**Resource:** [Stream](../resources/Stream.md)
**Stream filtered Posts**
**Operation ID:** `streamPosts`

Streams Posts in real-time matching the active rule set.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `backfill_minutes` | query | integer (int32) | No | The number of minutes of backfill requested. |
| `start_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The earliest UTC timestamp from which the Posts will be provided. |
| `end_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The latest UTC timestamp to which the Posts will be provided. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[FilteredStreamingTweetResponse](../schemas/Filtered/FilteredStreamingTweetResponse.md)

## Security

- **BearerToken**
