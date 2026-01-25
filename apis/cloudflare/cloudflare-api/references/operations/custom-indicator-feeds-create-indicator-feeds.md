# POST /accounts/{account_id}/intel/indicator-feeds

**Resource:** [Custom Indicator Feeds](../resources/Custom-Indicator-Feeds.md)
**Create new indicator feed**
**Operation ID:** `custom-indicator-feeds-create-indicator-feeds`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | custom-indicator-feeds_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [custom-indicator-feeds_create_feed](../schemas/custom-indicator-feeds/custom-indicator-feeds-create-feed.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create indicator feed response |
| 4XX | Get indicator feeds failure response |

**Success Response Schema:**

[custom-indicator-feeds_create_feed_response](../schemas/custom-indicator-feeds/custom-indicator-feeds-create-feed-response.md)

## Security

- **api_email**
- **api_key**
