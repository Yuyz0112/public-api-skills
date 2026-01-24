# POST /v1/billing/credit_grants

**Resource:** [billing](../resources/billing.md)
**Create a credit grant**
**Operation ID:** `PostBillingCreditGrants`

<p>Creates a credit grant.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing.credit_grant](../schemas/billing-credit/billing-credit-grant.md)

