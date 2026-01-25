# GET /radar/ranking/timeseries_groups

**Resource:** [Radar Domains Ranking](../resources/Radar-Domains-Ranking.md)
**Get domains rank time series**
**Operation ID:** `radar-get-ranking-domain-timeseries`

Retrieves domains rank over time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `rankingType` | query | enum: POPULAR, TRENDING_RISE, TRENDING_STEADY | No | The ranking type. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `location` | query | string[] | No | Filters results by location. Specify a comma-separated list of alpha-2 location codes. |
| `domains` | query | string[] | No | Filters results by domain name. Specify a comma-separated list of domain names. |
| `domainCategory` | query | string[] | No | Filters results by domain category. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
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
