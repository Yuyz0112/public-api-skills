# GET /2/likes/sample10/stream

**Resource:** [Likes](../resources/Likes.md)
**Stream sampled Likes**
**Operation ID:** `streamLikesSample10`

Streams a 10% sample of public Likes in real-time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `backfill_minutes` | query | integer (int32) | No | The number of minutes of backfill requested. |
| `partition` | query | integer (int32) | Yes | The partition number. |
| `start_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The earliest UTC timestamp to which the Likes will be provided. |
| `end_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The latest UTC timestamp to which the Posts will be provided. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[StreamingLikeResponseV2](../schemas/Streaming/StreamingLikeResponseV2.md)

## Security

- **BearerToken**
