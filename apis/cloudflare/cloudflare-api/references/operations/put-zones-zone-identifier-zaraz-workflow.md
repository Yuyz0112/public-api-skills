# PUT /zones/{zone_id}/settings/zaraz/workflow

**Resource:** [Zaraz](../resources/Zaraz.md)
**Update Zaraz workflow**
**Operation ID:** `put-zones-zone_identifier-zaraz-workflow`

Updates Zaraz workflow for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [zaraz_zaraz-workflow](../schemas/zaraz/zaraz-zaraz-workflow.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Zaraz workflow response |
| 4XX | Update Zaraz workflow response failure |

**Success Response Schema:**

[zaraz_zaraz-workflow-response](../schemas/zaraz/zaraz-zaraz-workflow-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
