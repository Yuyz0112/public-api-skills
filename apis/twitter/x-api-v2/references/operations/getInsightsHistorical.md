# GET /2/insights/historical

**Resource:** [Tweets](../resources/Tweets.md)
**Get historical Post insights**
**Operation ID:** `getInsightsHistorical`

Retrieves historical engagement metrics for specified Posts within a defined time range.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tweet_ids` | query | TweetId[] | Yes | List of PostIds for historical metrics. |
| `end_time` | query | string (date-time) | Yes | YYYY-MM-DDTHH:mm:ssZ. The UTC timestamp representing the end of the time range. |
| `start_time` | query | string (date-time) | Yes | YYYY-MM-DDTHH:mm:ssZ. The UTC timestamp representing the start of the time range. |
| `granularity` | query | enum: Daily, Hourly, Weekly... | Yes | granularity of metrics response. |
| `requested_metrics` | query | string[] | Yes | request metrics for historical request. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2InsightsHistoricalResponse](../schemas/Get/Get2InsightsHistoricalResponse.md)

## Security

- **OAuth2UserToken**: tweet.read
- **UserToken**
