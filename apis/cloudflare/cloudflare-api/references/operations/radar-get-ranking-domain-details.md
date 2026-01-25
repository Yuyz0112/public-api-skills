# GET /radar/ranking/domain/{domain}

**Resource:** [Radar Domains Ranking](../resources/Radar-Domains-Ranking.md)
**Get domain rank details**
**Operation ID:** `radar-get-ranking-domain-details`

Retrieves domain rank details. Cloudflare provides an ordered rank for the top 100 domains, but for the remainder it only provides ranking buckets like top 200 thousand, top one million, etc.. These are available through Radar datasets endpoints.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain` | path | string | Yes | Domain name. |
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `rankingType` | query | enum: POPULAR, TRENDING_RISE, TRENDING_STEADY | No | The ranking type. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `includeTopLocations` | query | boolean | No | Includes top locations in the response. |
| `date` | query | string[] | No | Filters results by the specified array of dates. |
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
