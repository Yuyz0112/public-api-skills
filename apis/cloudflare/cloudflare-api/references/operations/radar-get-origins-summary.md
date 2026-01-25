# GET /radar/origins/summary/{dimension}

**Resource:** [Radar Origins](../resources/Radar-Origins.md)
**Get origin metrics distribution by dimension**
**Operation ID:** `radar-get-origins-summary`

Retrieves an aggregated summary of origin metrics grouped by the specified dimension.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dimension` | path | enum: REGION, SUCCESS_RATE, PERCENTILE | Yes | Specifies the origin attribute by which to group the results. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `limitPerGroup` | query | integer | No | Limits the number of objects per group to the top items within the specified time range. When item count exceeds the limit, extra items appear grouped under an "other" category. |
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
