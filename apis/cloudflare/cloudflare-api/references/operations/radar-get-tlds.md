# GET /radar/tlds

**Resource:** [Radar Top-Level Domains](../resources/Radar-Top-Level-Domains.md)
**List TLDs**
**Operation ID:** `radar-get-tlds`

Retrieves a list of TLDs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `offset` | query | integer | No | Skips the specified number of objects before fetching the results. |
| `tldManager` | query | string | No | Filters results by TLD manager. |
| `tldType` | query | enum: GENERIC, COUNTRY_CODE, GENERIC_RESTRICTED... | No | Filters results by TLD type. |
| `tld` | query | string | No | Filters results by top-level domain. Specify a comma-separated list of TLDs. |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**
