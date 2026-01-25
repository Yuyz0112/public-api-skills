# GET /accounts/{account_id}/subscriptions

**Resource:** [Account Subscriptions](../resources/Account-Subscriptions.md)
**List Subscriptions**
**Operation ID:** `account-subscriptions-list-subscriptions`

Lists all of an account's subscriptions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | bill-subs-api_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Subscriptions response |
| 4XX | List Subscriptions response failure |

**Success Response Schema:**

[bill-subs-api_account_subscription_response_collection](../schemas/bill-subs-api/bill-subs-api-account-subscription-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
