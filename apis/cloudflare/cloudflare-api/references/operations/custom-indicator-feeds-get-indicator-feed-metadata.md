# GET /accounts/{account_id}/intel/indicator-feeds/{feed_id}

**Resource:** [Custom Indicator Feeds](../resources/Custom-Indicator-Feeds.md)
**Get indicator feed metadata**
**Operation ID:** `custom-indicator-feeds-get-indicator-feed-metadata`

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

[custom-indicator-feeds_indicator_feed_metadata_response](../schemas/custom-indicator-feeds/custom-indicator-feeds-indicator-feed-metadata-response.md)

## Security

- **api_email**
- **api_key**
