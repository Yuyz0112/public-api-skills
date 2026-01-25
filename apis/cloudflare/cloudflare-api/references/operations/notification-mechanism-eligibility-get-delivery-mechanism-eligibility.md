# GET /accounts/{account_id}/alerting/v3/destinations/eligible

**Resource:** [Notification Mechanism Eligibility](../resources/Notification-Mechanism-Eligibility.md)
**Get delivery mechanism eligibility**
**Operation ID:** `notification-mechanism-eligibility-get-delivery-mechanism-eligibility`

Get a list of all delivery mechanism types for which an account is eligible.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get delivery mechanism eligibility response |
| 4XX | Get delivery mechanism eligibility response failure |

**Success Response Schema:**

[aaa_schemas-response_collection](../schemas/aaa/aaa-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
