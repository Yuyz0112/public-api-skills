# PUT /accounts/{account_id}/subscriptions/{subscription_identifier}

**Resource:** [Account Subscriptions](../resources/Account-Subscriptions.md)
**Update Subscription**
**Operation ID:** `account-subscriptions-update-subscription`

Updates an account subscription.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subscription_identifier` | path | bill-subs-api_schemas-identifier | Yes |  |
| `account_id` | path | bill-subs-api_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [bill-subs-api_subscription-v2](../schemas/bill-subs-api/bill-subs-api-subscription-v2.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Subscription response |
| 4XX | Update Subscription response failure |

**Success Response Schema:**

[bill-subs-api_account_subscription_response_single](../schemas/bill-subs-api/bill-subs-api-account-subscription-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
