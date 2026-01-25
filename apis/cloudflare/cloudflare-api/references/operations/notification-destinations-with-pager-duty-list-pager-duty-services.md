# GET /accounts/{account_id}/alerting/v3/destinations/pagerduty

**Resource:** [Notification destinations with PagerDuty](../resources/Notification-destinations-with-PagerDuty.md)
**List PagerDuty services**
**Operation ID:** `notification-destinations-with-pager-duty-list-pager-duty-services`

Get a list of all configured PagerDuty services.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List PagerDuty services response |
| 4XX | List PagerDuty services response failure |

**Success Response Schema:**

[aaa_components-schemas-response_collection](../schemas/aaa/aaa-components-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
