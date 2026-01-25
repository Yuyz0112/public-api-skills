# GET /radar/ct/authorities/{ca_slug}

**Resource:** [Radar Certificate Transparency](../resources/Radar-Certificate-Transparency.md)
**Get certificate authority details**
**Operation ID:** `radar-get-certificate-authority-details`

Retrieves the requested CA information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ca_slug` | path | string | Yes | Certificate authority SHA256 fingerprint. |
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
