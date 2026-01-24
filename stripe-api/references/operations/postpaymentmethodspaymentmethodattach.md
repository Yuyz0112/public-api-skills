# POST /v1/payment_methods/{payment_method}/attach

**Resource:** [payment_methods](../resources/payment-methods.md)
**Attach a PaymentMethod to a Customer**
**Operation ID:** `PostPaymentMethodsPaymentMethodAttach`

<p>Attaches a PaymentMethod object to a Customer.</p>

<p>To attach a new PaymentMethod to a customer for future payments, we recommend you use a <a href="/docs/api/setup_intents">SetupIntent</a>
or a PaymentIntent with <a href="/docs/api/payment_intents/create#create_payment_intent-setup_future_usage">setup_future_usage</a>.
These approaches will perform any necessary steps to set up the PaymentMethod for future payments. Using the <code>/v1/payment_methods/:id/attach</code>
endpoint without first using a SetupIntent or PaymentIntent with <code>setup_future_usage</code> does not optimize the PaymentMethod for
future use, which makes later declines and payment friction more likely.
See <a href="/docs/payments/payment-intents#future-usage">Optimizing cards for future payments</a> for more information about setting up
future payments.</p>

<p>To use this PaymentMethod as the default for invoice or subscription payments,
set <a href="/docs/api/customers/update#update_customer-invoice_settings-default_payment_method"><code>invoice_settings.default_payment_method</code></a>,
on the Customer to the PaymentMethod’s ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `payment_method` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_method](../schemas/payment/payment-method.md)

