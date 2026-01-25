# GET /accounts/{account_id}/intel/indicator-feeds/{feed_id}/data

**Resource:** [Custom Indicator Feeds](../resources/Custom-Indicator-Feeds.md)
**Get indicator feed data**
**Operation ID:** `custom-indicator-feeds-get-indicator-feed-data`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | custom-indicator-feeds_identifier | Yes |  |
| `feed_id` | path | custom-indicator-feeds_feed_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get indicator feed metadata |
| 4XX | Get indicator feeds response failure |

## Security

- **api_email**
- **api_key**
