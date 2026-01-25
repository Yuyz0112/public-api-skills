# GET /2/insights/28hr

**Resource:** [Tweets](../resources/Tweets.md)
**Get 28-hour Post insights**
**Operation ID:** `getInsights28Hr`

Retrieves engagement metrics for specified Posts over the last 28 hours.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tweet_ids` | query | TweetId[] | Yes | List of PostIds for 28hr metrics. |
| `granularity` | query | enum: Daily, Hourly, Weekly... | Yes | granularity of metrics response. |
| `requested_metrics` | query | string[] | Yes | request metrics for historical request. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2Insights28hrResponse](../schemas/Get/Get2Insights28hrResponse.md)

## Security

- **OAuth2UserToken**: tweet.read
- **UserToken**
