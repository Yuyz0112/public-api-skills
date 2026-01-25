# GET /zones/{zone_id}/settings/zaraz/default

**Resource:** [Zaraz](../resources/Zaraz.md)
**Get default Zaraz configuration**
**Operation ID:** `get-zones-zone_identifier-zaraz-default`

Gets default Zaraz configuration for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Zaraz default configuration response |
| 4XX | Get Zaraz default configuration response failure |

**Success Response Schema:**

[zaraz_zaraz-config-response](../schemas/zaraz/zaraz-zaraz-config-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
