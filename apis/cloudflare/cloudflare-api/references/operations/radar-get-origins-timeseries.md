# GET /radar/origins/timeseries

**Resource:** [Radar Origins](../resources/Radar-Origins.md)
**Get origin metrics time series**
**Operation ID:** `radar-get-origins-timeseries`

Retrieves the time series of origin metrics for the specified origin.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `aggInterval` | query | enum: 15m, 1h, 1d... | No | Aggregation interval of the results (e.g., in 15 minutes or 1 hour intervals). Refer to [Aggregation intervals](https://developers.cloudflare.com/radar/concepts/aggregation-intervals/). |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `origin` | query | string[] | Yes | Filters results by origin. |
| `metric` | query | enum: CONNECTION_FAILURES, REQUESTS, RESPONSE_HEADER_RECEIVE_DURATION... | Yes | Specifies the metric to retrieve. |
| `region` | query | string[] | No | Filters results by origin region. |
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
