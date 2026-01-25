# GET /radar/entities/ip

**Resource:** [Radar IP](../resources/Radar-IP.md)
**Get IP address details**
**Operation ID:** `radar-get-entities-ip`

Retrieves IP address information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ip` | query | string (ip) | Yes | IP address. |
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
