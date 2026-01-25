# GET /v1/tax_ids/{id}

**Resource:** [tax_ids](../resources/tax-ids.md)
**Retrieve a tax ID**
**Operation ID:** `GetTaxIdsId`

<p>Retrieves an account or customer <code>tax_id</code> object.</p>

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

[tax_id](../schemas/tax/tax-id.md)

