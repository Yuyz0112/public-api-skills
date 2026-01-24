# POST /v1/setup_intents/{intent}/confirm

**Resource:** [setup_intents](../resources/setup-intents.md)
**Confirm a SetupIntent**
**Operation ID:** `PostSetupIntentsIntentConfirm`

<p>Confirm that your customer intends to set up the current or
provided payment method. For example, you would confirm a SetupIntent
when a customer hits the “Save” button on a payment method management
page on your website.</p>

<p>If the selected payment method does not require any additional
steps from the customer, the SetupIntent will transition to the
<code>succeeded</code> status.</p>

<p>Otherwise, it will transition to the <code>requires_action</code> status and
suggest additional actions via <code>next_action</code>. If setup fails,
the SetupIntent will transition to the
<code>requires_payment_method</code> status or the <code>canceled</code> status if the
confirmation limit is reached.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `intent` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[setup_intent](../schemas/setup/setup-intent.md)

