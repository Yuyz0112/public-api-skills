# GET /v1/customers/{customer}

**Resource:** [customers](../resources/customers.md)
**Retrieve a customer**
**Operation ID:** `GetCustomersCustomer`

<p>Retrieves a Customer object.</p>

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

