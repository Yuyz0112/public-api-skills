# POST /v1/issuing/disputes/{dispute}

**Resource:** [issuing](../resources/issuing.md)
**Update a dispute**
**Operation ID:** `PostIssuingDisputesDispute`

<p>Updates the specified Issuing <code>Dispute</code> object by setting the values of the parameters passed. Any parameters not provided will be left unchanged. Properties on the <code>evidence</code> object can be unset by passing in an empty string.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dispute` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.dispute](../schemas/issuing-dispute/issuing-dispute.md)

