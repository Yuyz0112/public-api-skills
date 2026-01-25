# GET /zones/{zone_id}/settings/zaraz/config

**Resource:** [Zaraz](../resources/Zaraz.md)
**Get Zaraz configuration**
**Operation ID:** `get-zones-zone_identifier-zaraz-config`

Gets latest Zaraz configuration for a zone. It can be preview or published configuration, whichever was the last updated. Secret variables values will not be included.

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

[zaraz_zaraz-config-response](../schemas/zaraz/zaraz-zaraz-config-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
