# GET /v1/tax/associations/find

**Resource:** [tax](../resources/tax.md)
**Find a Tax Association**
**Operation ID:** `GetTaxAssociationsFind`

<p>Finds a tax association object by PaymentIntent id.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `payment_intent` | query | string | Yes | Valid [PaymentIntent](https://docs.stripe.com/api/payment_intents/object) id |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax.association](../schemas/tax-association/tax-association.md)

