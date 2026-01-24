# GET /v1/issuing/disputes/{dispute}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve a dispute**
**Operation ID:** `GetIssuingDisputesDispute`

<p>Retrieves an Issuing <code>Dispute</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dispute` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.dispute](../schemas/issuing-dispute/issuing-dispute.md)

