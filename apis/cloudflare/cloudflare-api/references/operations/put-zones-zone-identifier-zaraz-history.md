# PUT /zones/{zone_id}/settings/zaraz/history

**Resource:** [Zaraz](../resources/Zaraz.md)
**Restore Zaraz historical configuration by ID**
**Operation ID:** `put-zones-zone_identifier-zaraz-history`

Restores a historical published Zaraz configuration by ID for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Restore Zaraz historical configuration by ID response |
| 4XX | Restore Zaraz historical configuration by ID failure |

**Success Response Schema:**

[zaraz_zaraz-config-response](../schemas/zaraz/zaraz-zaraz-config-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
