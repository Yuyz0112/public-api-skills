# GET /zones/{zone_id}/settings/zaraz/history/configs

**Resource:** [Zaraz](../resources/Zaraz.md)
**Get Zaraz historical configurations by ID(s)**
**Operation ID:** `get-zones-zone_identifier-zaraz-config-history`

Gets a history of published Zaraz configurations by ID(s) for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |
| `ids` | query | integer[] | Yes | Comma separated list of Zaraz configuration IDs |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Zaraz historical configurations by ID(s) response |
| 4XX | Get Zaraz historical configurations by ID(s) failure |

**Success Response Schema:**

[zaraz_zaraz-config-history-response](../schemas/zaraz/zaraz-zaraz-config-history-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
