# DELETE /zones/{zone_id}

**Resource:** [Zone](../resources/Zone.md)
**Delete Zone**
**Operation ID:** `zones-0-delete`

Deletes an existing zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Zone response. |
| 4XX | Delete Zone response failure. |

**Success Response Schema:**

[zones_api-response-single-id](../schemas/zones/zones-api-response-single-id.md)

## Security

- **api_token**
- **api_email**
- **api_key**
