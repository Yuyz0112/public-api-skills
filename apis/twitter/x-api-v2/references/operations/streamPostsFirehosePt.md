# GET /2/tweets/firehose/stream/lang/pt

**Resource:** [Stream](../resources/Stream.md)
**Stream Portuguese Posts**
**Operation ID:** `streamPostsFirehosePt`

Streams all public Portuguese-language Posts in real-time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `backfill_minutes` | query | integer (int32) | No | The number of minutes of backfill requested. |
| `partition` | query | integer (int32) | Yes | The partition number. |
| `start_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The earliest UTC timestamp to which the Posts will be provided. |
| `end_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The latest UTC timestamp to which the Posts will be provided. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[StreamingTweetResponse](../schemas/Streaming/StreamingTweetResponse.md)

## Security

- **BearerToken**
