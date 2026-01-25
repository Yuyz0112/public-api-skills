# ActivityStreamingResponse

An activity event or error that can be returned by the x activity streaming API.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |
| `errors` | Problem[] | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event_type` | string | No |  |
| `event_uuid` | [ActivityEventId](ActivityEventId.md) | No |  |
| `filter` | [ActivitySubscriptionFilter](ActivitySubscriptionFilter.md) | No |  |
| `payload` | [ActivityStreamingResponsePayload](ActivityStreamingResponsePayload.md) | No |  |
| `tag` | string | No |  |

