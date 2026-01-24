# GET /v1/customers/{customer}/discount

**Resource:** [customers](../resources/customers.md)
**Operation ID:** `GetCustomersCustomerDiscount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[discount](../schemas/discount/discount.md)

