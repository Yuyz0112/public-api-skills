# GET /zones/{zone_id}/settings/zaraz/export

**Resource:** [Zaraz](../resources/Zaraz.md)
**Export Zaraz configuration**
**Operation ID:** `get-zones-zone_identifier-zaraz-export`

Exports full current published Zaraz configuration for a zone, secret variables included.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Zaraz configuration response |
| 4XX | Get Zaraz configuration response failure |

**Success Response Schema:**

[zaraz_zaraz-config-return](../schemas/zaraz/zaraz-zaraz-config-return.md)

## Security

- **api_token**
- **api_email**
- **api_key**
