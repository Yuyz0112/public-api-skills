# POST /zones/{zone_id}/subscription

**Resource:** [Zone Subscription](../resources/Zone-Subscription.md)
**Create Zone Subscription**
**Operation ID:** `zone-subscription-create-zone-subscription`

Create a zone subscription, either plan or add-ons.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | bill-subs-api_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [bill-subs-api_subscription-v2](../schemas/bill-subs-api/bill-subs-api-subscription-v2.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Zone Subscription response |
| 4XX | Create Zone Subscription response failure |

**Success Response Schema:**

[bill-subs-api_zone_subscription_response_single](../schemas/bill-subs-api/bill-subs-api-zone-subscription-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
