# GET /2/tweets/sample/stream

**Resource:** [Stream](../resources/Stream.md)
**Stream sampled Posts**
**Operation ID:** `streamPostsSample`

Streams a 1% sample of public Posts in real-time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `backfill_minutes` | query | integer (int32) | No | The number of minutes of backfill requested. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[StreamingTweetResponse](../schemas/Streaming/StreamingTweetResponse.md)

## Security

- **BearerToken**
