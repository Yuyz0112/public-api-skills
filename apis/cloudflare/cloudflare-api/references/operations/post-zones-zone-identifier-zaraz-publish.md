# POST /zones/{zone_id}/settings/zaraz/publish

**Resource:** [Zaraz](../resources/Zaraz.md)
**Publish Zaraz preview configuration**
**Operation ID:** `post-zones-zone_identifier-zaraz-publish`

Publish current Zaraz preview configuration for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zaraz_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Zaraz workflow response |
| 4XX | Update Zaraz workflow response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
