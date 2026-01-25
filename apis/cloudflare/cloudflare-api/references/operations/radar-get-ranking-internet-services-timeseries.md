# GET /radar/ranking/internet_services/timeseries_groups

**Resource:** [Radar Internet Services Ranking](../resources/Radar-Internet-Services-Ranking.md)
**Get Internet services rank time series**
**Operation ID:** `radar-get-ranking-internet-services-timeseries`

Retrieves Internet Services rank update changes over time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `serviceCategory` | query | string[] | No | Filters results by Internet service category. |
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
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
