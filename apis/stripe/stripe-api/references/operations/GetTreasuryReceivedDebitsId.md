# GET /v1/treasury/received_debits/{id}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve a ReceivedDebit**
**Operation ID:** `GetTreasuryReceivedDebitsId`

<p>Retrieves the details of an existing ReceivedDebit by passing the unique ReceivedDebit ID from the ReceivedDebit list</p>

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

[treasury.received_debit](../schemas/treasury-received/treasury-received-debit.md)

