# GET /radar/bots/crawlers/timeseries_groups/{dimension}

**Resource:** [Radar Web Crawlers](../resources/Radar-Web-Crawlers.md)
**Get time series of crawler HTTP request distribution by dimension**
**Operation ID:** `radar-get-crawlers-timeseries-group`

Retrieves the distribution of HTTP requests from crawlers, grouped by chosen the specified dimension over time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dimension` | path | enum: CLIENT_TYPE, USER_AGENT, REFERER... | Yes | Specifies the attribute by which to group the results. |
| `aggInterval` | query | enum: 15m, 1h, 1d... | No | Aggregation interval of the results (e.g., in 15 minutes or 1 hour intervals). Refer to [Aggregation intervals](https://developers.cloudflare.com/radar/concepts/aggregation-intervals/). |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `limitPerGroup` | query | integer | No | Limits the number of objects per group to the top items within the specified time range. When item count exceeds the limit, extra items appear grouped under an "other" category. |
| `botOperator` | query | string[] | No | Filters results by bot operator. |
| `vertical` | query | string[] | No | Filters results by vertical. |
| `industry` | query | string[] | No | Filters results by industry. |
| `clientType` | query | string[] | No | Filters results by agent type. |
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
