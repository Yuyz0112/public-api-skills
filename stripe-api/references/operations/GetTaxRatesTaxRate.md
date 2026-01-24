# GET /v1/tax_rates/{tax_rate}

**Resource:** [tax_rates](../resources/tax-rates.md)
**Retrieve a tax rate**
**Operation ID:** `GetTaxRatesTaxRate`

<p>Retrieves a tax rate with the given ID</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `tax_rate` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax_rate](../schemas/tax/tax-rate.md)

