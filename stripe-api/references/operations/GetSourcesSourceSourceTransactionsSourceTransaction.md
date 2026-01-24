# GET /v1/sources/{source}/source_transactions/{source_transaction}

**Resource:** [sources](../resources/sources.md)
**Retrieve a source transaction**
**Operation ID:** `GetSourcesSourceSourceTransactionsSourceTransaction`

<p>Retrieve an existing source transaction object. Supply the unique source ID from a source creation request and the source transaction ID and Stripe will return the corresponding up-to-date source object information.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `source` | path | string | Yes |  |
| `source_transaction` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[source_transaction](../schemas/source/source-transaction.md)

