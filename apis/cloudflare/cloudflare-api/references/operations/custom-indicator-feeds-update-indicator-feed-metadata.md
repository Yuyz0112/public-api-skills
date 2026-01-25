# PUT /accounts/{account_id}/intel/indicator-feeds/{feed_id}

**Resource:** [Custom Indicator Feeds](../resources/Custom-Indicator-Feeds.md)
**Update indicator feed metadata**
**Operation ID:** `custom-indicator-feeds-update-indicator-feed-metadata`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | custom-indicator-feeds_identifier | Yes |  |
| `feed_id` | path | custom-indicator-feeds_feed_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [custom-indicator-feeds_update_public_field_request](../schemas/custom-indicator-feeds/custom-indicator-feeds-update-public-field-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get update public field response |
| 4XX | Get update public field response failure |

**Success Response Schema:**

[custom-indicator-feeds_update_public_field_response](../schemas/custom-indicator-feeds/custom-indicator-feeds-update-public-field-response.md)

## Security

- **api_email**
- **api_key**
