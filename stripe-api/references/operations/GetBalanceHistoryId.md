# GET /v1/balance/history/{id}

**Resource:** [balance](../resources/balance.md)
**Retrieve a balance transaction**
**Operation ID:** `GetBalanceHistoryId`

<p>Retrieves the balance transaction with the given ID.</p>

<p>Note that this endpoint previously used the path <code>/v1/balance/history/:id</code>.</p>

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

[balance_transaction](../schemas/balance/balance-transaction.md)

