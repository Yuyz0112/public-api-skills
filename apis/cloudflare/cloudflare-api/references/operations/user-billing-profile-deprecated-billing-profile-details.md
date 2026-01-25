# GET /user/billing/profile

**Resource:** [User Billing Profile](../resources/User-Billing-Profile.md)
**Billing Profile Details**
**Operation ID:** `user-billing-profile-(-deprecated)-billing-profile-details`
⚠️ **Deprecated**

Accesses your billing profile object.

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
