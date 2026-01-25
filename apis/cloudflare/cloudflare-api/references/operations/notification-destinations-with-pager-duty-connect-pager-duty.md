# POST /accounts/{account_id}/alerting/v3/destinations/pagerduty/connect

**Resource:** [Notification destinations with PagerDuty](../resources/Notification-destinations-with-PagerDuty.md)
**Create PagerDuty integration token**
**Operation ID:** `notification-destinations-with-pager-duty-connect-pager-duty`

Creates a new token for integrating with PagerDuty.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Token for PagerDuty integration |
| 4XX | Create a token for PagerDuty integration failure |

**Success Response Schema:**

[aaa_sensitive_id_response](../schemas/aaa/aaa-sensitive-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
