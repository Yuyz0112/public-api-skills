# GET /accounts/{account_id}/alerting/v3/history

**Resource:** [Notification History](../resources/Notification-History.md)
**List History**
**Operation ID:** `notification-history-list-history`

Gets a list of history records for notifications sent to an account. The records are displayed for last `x` number of days based on the zone plan (free = 30, pro = 30, biz = 30, ent = 90).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |
| `per_page` | query | aaa_per_page | No |  |
| `before` | query | aaa_before | No |  |
| `page` | query | number | No |  |
| `since` | query | string (date-time) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List History response |
| 4XX | List History response failure |

**Success Response Schema:**

[aaa_history_components-schemas-response_collection](../schemas/aaa/aaa-history-components-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
