# POST /v1/issuing/disputes/{dispute}/submit

**Resource:** [issuing](../resources/issuing.md)
**Submit a dispute**
**Operation ID:** `PostIssuingDisputesDisputeSubmit`

<p>Submits an Issuing <code>Dispute</code> to the card network. Stripe validates that all evidence fields required for the dispute’s reason are present. For more details, see <a href="/docs/issuing/purchases/disputes#dispute-reasons-and-evidence">Dispute reasons and evidence</a>.</p>

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

