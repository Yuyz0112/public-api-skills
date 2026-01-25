# POST /accounts/{account_id}/subscriptions

**Resource:** [Account Subscriptions](../resources/Account-Subscriptions.md)
**Create Subscription**
**Operation ID:** `account-subscriptions-create-subscription`

Creates an account subscription.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | bill-subs-api_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [bill-subs-api_subscription-v2](../schemas/bill-subs-api/bill-subs-api-subscription-v2.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Subscription response |
| 4XX | Create Subscription response failure |

**Success Response Schema:**

[bill-subs-api_account_subscription_response_single](../schemas/bill-subs-api/bill-subs-api-account-subscription-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
