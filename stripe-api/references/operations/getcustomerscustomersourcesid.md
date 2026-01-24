# GET /v1/customers/{customer}/sources/{id}

**Resource:** [customers](../resources/customers.md)
**Operation ID:** `GetCustomersCustomerSourcesId`

<p>Retrieve a specified source for a given customer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
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

[payment_source](../schemas/payment/payment-source.md)

