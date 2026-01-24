# DELETE /v1/tax_ids/{id}

**Resource:** [tax_ids](../resources/tax-ids.md)
**Delete a tax ID**
**Operation ID:** `DeleteTaxIdsId`

<p>Deletes an existing account or customer <code>tax_id</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_tax_id](../schemas/deleted/deleted-tax-id.md)

