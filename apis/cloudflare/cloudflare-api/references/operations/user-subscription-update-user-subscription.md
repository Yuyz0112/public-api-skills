# PUT /user/subscriptions/{identifier}

**Resource:** [User Subscription](../resources/User-Subscription.md)
**Update User Subscription**
**Operation ID:** `user-subscription-update-user-subscription`

Updates a user's subscriptions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | bill-subs-api_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [bill-subs-api_subscription-v2](../schemas/bill-subs-api/bill-subs-api-subscription-v2.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update User Subscription response |
| 4XX | Update User Subscription response failure |

**Success Response Schema:**

[bill-subs-api_user_subscription_response_single](../schemas/bill-subs-api/bill-subs-api-user-subscription-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
