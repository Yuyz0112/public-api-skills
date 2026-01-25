# GET /accounts/{account_id}/alerting/v3/policies

**Resource:** [Notification policies](../resources/Notification-policies.md)
**List Notification policies**
**Operation ID:** `notification-policies-list-notification-policies`

Get a list of all Notification policies.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Notification policies response |
| 4XX | List Notification policies response failure |

**Success Response Schema:**

[aaa_policies_components-schemas-response_collection](../schemas/aaa/aaa-policies-components-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
