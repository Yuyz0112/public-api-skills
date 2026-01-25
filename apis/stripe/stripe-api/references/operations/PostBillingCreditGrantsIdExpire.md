# POST /v1/billing/credit_grants/{id}/expire

**Resource:** [billing](../resources/billing.md)
**Expire a credit grant**
**Operation ID:** `PostBillingCreditGrantsIdExpire`

<p>Expires a credit grant.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Unique identifier for the object. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[billing.credit_grant](../schemas/billing-credit/billing-credit-grant.md)

