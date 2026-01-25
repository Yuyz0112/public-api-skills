# GET /accounts/{account_id}/intel/indicator-feeds/permissions/view

**Resource:** [Custom Indicator Feeds](../resources/Custom-Indicator-Feeds.md)
**List indicator feed permissions**
**Operation ID:** `custom-indicator-feeds-view-permissions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | custom-indicator-feeds_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get indicator feed metadata |
| 4XX | Get indicator feeds response failure |

**Success Response Schema:**

[custom-indicator-feeds_permission_list_item_response](../schemas/custom-indicator-feeds/custom-indicator-feeds-permission-list-item-response.md)

## Security

- **api_email**
- **api_key**
