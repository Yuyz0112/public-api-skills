# GET /radar/tlds/{tld}

**Resource:** [Radar Top-Level Domains](../resources/Radar-Top-Level-Domains.md)
**Get TLD details**
**Operation ID:** `radar-get-tld-details`

Retrieves the requested TLD information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tld` | path | string | Yes | Top-level domain. |
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
