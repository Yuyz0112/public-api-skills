# PUT /zones/{zone_id}/settings/zaraz/config

**Resource:** [Zaraz](../resources/Zaraz.md)
**Update Zaraz configuration**
**Operation ID:** `put-zones-zone_identifier-zaraz-config`

Updates Zaraz configuration for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [zaraz_zaraz-config-body](../schemas/zaraz/zaraz-zaraz-config-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Zaraz configuration response |
| 4XX | Update Zaraz configuration response failure |

**Success Response Schema:**

[zaraz_zaraz-config-response](../schemas/zaraz/zaraz-zaraz-config-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
