# GET /zones/{zone_id}/subscription

**Resource:** [Zone Subscription](../resources/Zone-Subscription.md)
**Zone Subscription Details**
**Operation ID:** `zone-subscription-zone-subscription-details`

Lists zone subscription details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | bill-subs-api_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Zone Subscription Details response |
| 4XX | Zone Subscription Details response failure |

**Success Response Schema:**

[bill-subs-api_zone_subscription_response_single](../schemas/bill-subs-api/bill-subs-api-zone-subscription-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
