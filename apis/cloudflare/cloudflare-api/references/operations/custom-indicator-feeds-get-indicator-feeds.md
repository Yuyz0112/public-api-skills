# GET /accounts/{account_id}/intel/indicator-feeds

**Resource:** [Custom Indicator Feeds](../resources/Custom-Indicator-Feeds.md)
**Get indicator feeds owned by this account**
**Operation ID:** `custom-indicator-feeds-get-indicator-feeds`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | custom-indicator-feeds_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get indicator feeds response |
| 4XX | Get indicator feeds response failure |

**Success Response Schema:**

[custom-indicator-feeds_indicator_feed_response](../schemas/custom-indicator-feeds/custom-indicator-feeds-indicator-feed-response.md)

## Security

- **api_email**
- **api_key**
