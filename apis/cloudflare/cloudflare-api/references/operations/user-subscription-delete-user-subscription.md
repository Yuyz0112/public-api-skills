# DELETE /user/subscriptions/{identifier}

**Resource:** [User Subscription](../resources/User-Subscription.md)
**Delete User Subscription**
**Operation ID:** `user-subscription-delete-user-subscription`

Deletes a user's subscription.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | bill-subs-api_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete User Subscription response |
| 4XX | Delete User Subscription response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
