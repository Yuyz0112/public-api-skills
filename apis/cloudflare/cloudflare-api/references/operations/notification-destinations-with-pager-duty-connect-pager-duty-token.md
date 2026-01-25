# GET /accounts/{account_id}/alerting/v3/destinations/pagerduty/connect/{token_id}

**Resource:** [Notification destinations with PagerDuty](../resources/Notification-destinations-with-PagerDuty.md)
**Connect PagerDuty**
**Operation ID:** `notification-destinations-with-pager-duty-connect-pager-duty-token`

Links PagerDuty with the account using the integration token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |
| `token_id` | path | aaa_integration-token | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a Notification policy response |
| 4XX | Create a Notification policy response failure |

**Success Response Schema:**

[aaa_id_response](../schemas/aaa/aaa-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
