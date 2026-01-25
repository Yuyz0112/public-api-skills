# GET /accounts/{account_id}/billing/profile

**Resource:** [Account Billing Profile](../resources/Account-Billing-Profile.md)
**Billing Profile Details**
**Operation ID:** `account-billing-profile-(-deprecated)-billing-profile-details`
⚠️ **Deprecated**

Gets the current billing profile for the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | bill-subs-api_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Billing Profile Details response |
| 4XX | Billing Profile Details response failure |

**Success Response Schema:**

[bill-subs-api_billing_response_single](../schemas/bill-subs-api/bill-subs-api-billing-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
