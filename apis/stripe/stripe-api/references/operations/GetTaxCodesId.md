# GET /v1/tax_codes/{id}

**Resource:** [tax_codes](../resources/tax-codes.md)
**Retrieve a tax code**
**Operation ID:** `GetTaxCodesId`

<p>Retrieves the details of an existing tax code. Supply the unique tax code ID and Stripe will return the corresponding tax code information.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax_code](../schemas/tax/tax-code.md)

