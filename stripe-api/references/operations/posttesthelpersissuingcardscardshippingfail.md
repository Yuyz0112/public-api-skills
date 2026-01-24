# POST /v1/test_helpers/issuing/cards/{card}/shipping/fail

**Resource:** [test_helpers](../resources/test-helpers.md)
**Fail a testmode card**
**Operation ID:** `PostTestHelpersIssuingCardsCardShippingFail`

<p>Updates the shipping status of the specified Issuing <code>Card</code> object to <code>failure</code>.</p>

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

