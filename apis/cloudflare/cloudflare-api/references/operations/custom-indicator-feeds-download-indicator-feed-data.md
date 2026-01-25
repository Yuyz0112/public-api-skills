# GET /accounts/{account_id}/intel/indicator-feeds/{feed_id}/download

**Resource:** [Custom Indicator Feeds](../resources/Custom-Indicator-Feeds.md)
**Download indicator feed data**
**Operation ID:** `custom-indicator-feeds-download-indicator-feed-data`

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

**Success Response Schema:**

[custom-indicator-feeds_update_feed_response](../schemas/custom-indicator-feeds/custom-indicator-feeds-update-feed-response.md)

## Security

- **api_email**
- **api_key**
