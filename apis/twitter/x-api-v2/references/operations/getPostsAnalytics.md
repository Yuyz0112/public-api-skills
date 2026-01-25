# GET /2/tweets/analytics

**Resource:** [Tweets](../resources/Tweets.md)
**Get Post analytics**
**Operation ID:** `getPostsAnalytics`

Retrieves analytics data for specified Posts within a defined time range.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | TweetId[] | Yes | A comma separated list of Post IDs. Up to 100 are allowed in a single request. |
| `end_time` | query | string (date-time) | Yes | YYYY-MM-DDTHH:mm:ssZ. The UTC timestamp representing the end of the time range. |
| `start_time` | query | string (date-time) | Yes | YYYY-MM-DDTHH:mm:ssZ. The UTC timestamp representing the start of the time range. |
| `granularity` | query | enum: hourly, daily, weekly... | Yes | The granularity for the search counts results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Analytics](../schemas/Analytics/Analytics.md)

## Security

- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**
