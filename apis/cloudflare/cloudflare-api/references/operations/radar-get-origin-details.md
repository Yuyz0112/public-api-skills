# GET /radar/origins/{slug}

**Resource:** [Radar Origins](../resources/Radar-Origins.md)
**Get Origin details**
**Operation ID:** `radar-get-origin-details`

Retrieves the requested origin information with its regions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | enum: AMAZON, GOOGLE, MICROSOFT... | Yes | Origin slug. |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 404 | Not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
