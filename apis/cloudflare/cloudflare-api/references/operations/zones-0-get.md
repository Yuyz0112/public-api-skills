# GET /zones/{zone_id}

**Resource:** [Zone](../resources/Zone.md)
**Zone Details**
**Operation ID:** `zones-0-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Zone Details response. |
| 4XX | Zone Details response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
