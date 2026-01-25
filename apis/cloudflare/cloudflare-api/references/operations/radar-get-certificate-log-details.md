# GET /radar/ct/logs/{log_slug}

**Resource:** [Radar Certificate Transparency](../resources/Radar-Certificate-Transparency.md)
**Get certificate log details**
**Operation ID:** `radar-get-certificate-log-details`

Retrieves the requested certificate log information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `log_slug` | path | string | Yes | Certificate log slug. |
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
