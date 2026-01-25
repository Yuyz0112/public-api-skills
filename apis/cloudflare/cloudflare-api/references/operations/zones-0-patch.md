# PATCH /zones/{zone_id}

**Resource:** [Zone](../resources/Zone.md)
**Edit Zone**
**Operation ID:** `zones-0-patch`

Edits a zone. Only one zone property can be changed at a time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit Zone response. |
| 4XX | Edit Zone response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
