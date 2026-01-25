# GET /zones/{zone_id}/settings/zaraz/workflow

**Resource:** [Zaraz](../resources/Zaraz.md)
**Get Zaraz workflow**
**Operation ID:** `get-zones-zone_identifier-zaraz-workflow`

Gets Zaraz workflow for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Zaraz workflow response |
| 4XX | Get Zaraz workflow response failure |

**Success Response Schema:**

[zaraz_zaraz-workflow-response](../schemas/zaraz/zaraz-zaraz-workflow-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
