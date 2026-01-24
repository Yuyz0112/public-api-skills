# POST /v1/test_helpers/issuing/cards/{card}/shipping/submit

**Resource:** [test_helpers](../resources/test-helpers.md)
**Submit a testmode card**
**Operation ID:** `PostTestHelpersIssuingCardsCardShippingSubmit`

<p>Updates the shipping status of the specified Issuing <code>Card</code> object to <code>submitted</code>. This method requires Stripe Version ‘2024-09-30.acacia’ or later.</p>

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

