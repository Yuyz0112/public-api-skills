# POST /v1/test_helpers/issuing/cards/{card}/shipping/deliver

**Resource:** [test_helpers](../resources/test-helpers.md)
**Deliver a testmode card**
**Operation ID:** `PostTestHelpersIssuingCardsCardShippingDeliver`

<p>Updates the shipping status of the specified Issuing <code>Card</code> object to <code>delivered</code>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `card` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.card](../schemas/issuing-card/issuing-card.md)

