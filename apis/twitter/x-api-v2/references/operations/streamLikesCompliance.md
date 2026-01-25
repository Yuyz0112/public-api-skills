# GET /2/likes/compliance/stream

**Resource:** [Compliance](../resources/Compliance.md)
**Stream Likes compliance data**
**Operation ID:** `streamLikesCompliance`

Streams all compliance data related to Likes for Users.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `backfill_minutes` | query | integer (int32) | No | The number of minutes of backfill requested. |
| `start_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The earliest UTC timestamp from which the Likes Compliance events will be provided. |
| `end_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The latest UTC timestamp from which the Likes Compliance events will be provided. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[LikesComplianceStreamResponse](../schemas/Likes/LikesComplianceStreamResponse.md)

## Security

- **BearerToken**
