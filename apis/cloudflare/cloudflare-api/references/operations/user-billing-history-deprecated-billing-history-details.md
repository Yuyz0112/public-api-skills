# GET /user/billing/history

**Resource:** [User Billing History](../resources/User-Billing-History.md)
**Billing History Details**
**Operation ID:** `user-billing-history-(-deprecated)-billing-history-details`
⚠️ **Deprecated**

Accesses your billing history object.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: type, occurred_at, action | No |  |
| `occurred_at` | query | bill-subs-api_occurred_at | No |  |
| `type` | query | string | No |  |
| `action` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Billing History Details response |
| 4XX | Billing History Details response failure |

**Success Response Schema:**

[bill-subs-api_billing_history_collection](../schemas/bill-subs-api/bill-subs-api-billing-history-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
