# GET /v1/disputes/{dispute}

**Resource:** [disputes](../resources/disputes.md)
**Retrieve a dispute**
**Operation ID:** `GetDisputesDispute`

<p>Retrieves the dispute with the given ID.</p>

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

[dispute](../schemas/dispute/dispute.md)

