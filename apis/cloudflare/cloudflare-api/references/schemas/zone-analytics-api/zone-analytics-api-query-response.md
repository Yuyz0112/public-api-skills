# zone-analytics-api_query_response

The exact parameters/timestamps the analytics service used to return data.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `since` | [zone-analytics-api_since](zone-analytics-api-since.md) | No |  |
| `time_delta` | integer | No | The amount of time (in minutes) that each data point in the timeseries represents. The granularity of the time-series returned (e.g. each bucket in the time series representing 1-minute vs 1-day) is calculated by the API based on the time-range provided to the API. |
| `until` | [zone-analytics-api_until](zone-analytics-api-until.md) | No |  |

