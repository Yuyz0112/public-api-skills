# GET /v1/treasury/received_credits/{id}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve a ReceivedCredit**
**Operation ID:** `GetTreasuryReceivedCreditsId`

<p>Retrieves the details of an existing ReceivedCredit by passing the unique ReceivedCredit ID from the ReceivedCredit list.</p>

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

[treasury.received_credit](../schemas/treasury-received/treasury-received-credit.md)

