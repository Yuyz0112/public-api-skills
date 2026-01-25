# DELETE /accounts/{account_id}/subscriptions/{subscription_identifier}

**Resource:** [Account Subscriptions](../resources/Account-Subscriptions.md)
**Delete Subscription**
**Operation ID:** `account-subscriptions-delete-subscription`

Deletes an account's subscription.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subscription_identifier` | path | bill-subs-api_schemas-identifier | Yes |  |
| `account_id` | path | bill-subs-api_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Subscription response |
| 4XX | Delete Subscription response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
