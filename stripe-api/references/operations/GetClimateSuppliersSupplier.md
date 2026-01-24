# GET /v1/climate/suppliers/{supplier}

**Resource:** [climate](../resources/climate.md)
**Retrieve a supplier**
**Operation ID:** `GetClimateSuppliersSupplier`

<p>Retrieves a Climate supplier object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `supplier` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[climate.supplier](../schemas/climate-supplier/climate-supplier.md)

