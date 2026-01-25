# DELETE /accounts/{account_id}/alerting/v3/destinations/pagerduty

**Resource:** [Notification destinations with PagerDuty](../resources/Notification-destinations-with-PagerDuty.md)
**Delete PagerDuty Services**
**Operation ID:** `notification-destinations-with-pager-duty-delete-pager-duty-services`

Deletes all the PagerDuty Services connected to the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete PagerDuty Services response |
| 4XX | Delete PagerDuty Services response failure |

**Success Response Schema:**

[aaa_schemas-api-response-common](../schemas/aaa/aaa-schemas-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
