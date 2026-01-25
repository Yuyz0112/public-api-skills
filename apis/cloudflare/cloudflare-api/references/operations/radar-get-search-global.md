# GET /radar/search/global

**Resource:** [Radar Search](../resources/Radar-Search.md)
**Search for locations, ASes, reports, and more**
**Operation ID:** `radar-get-search-global`

Searches for locations, autonomous systems, reports, bots, certificate logs, certificate authorities, industries and verticals

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `limitPerGroup` | query | number | No | Limits the number of objects per search category. |
| `query` | query | string | Yes | String used to perform the search operation. |
| `include` | query | string[] | No | Search types included in results. |
| `exclude` | query | string[] | No | Search types excluded from results. |
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
