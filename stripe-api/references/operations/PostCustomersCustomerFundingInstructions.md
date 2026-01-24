# POST /v1/customers/{customer}/funding_instructions

**Resource:** [customers](../resources/customers.md)
**Create or retrieve funding instructions for a customer cash balance**
**Operation ID:** `PostCustomersCustomerFundingInstructions`

<p>Retrieve funding instructions for a customer cash balance. If funding instructions do not yet exist for the customer, new
funding instructions will be created. If funding instructions have already been created for a given customer, the same
funding instructions will be retrieved. In other words, we will return the same funding instructions each time.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[funding_instructions](../schemas/funding/funding-instructions.md)

