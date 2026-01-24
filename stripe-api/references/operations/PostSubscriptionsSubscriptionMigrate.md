# POST /v1/subscriptions/{subscription}/migrate

**Resource:** [subscriptions](../resources/subscriptions.md)
**Migrate a subscription**
**Operation ID:** `PostSubscriptionsSubscriptionMigrate`

<p>Upgrade the billing_mode of an existing subscription.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subscription` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[subscription](../schemas/subscription/subscription.md)

