# GET /v1/credit_notes/preview

**Resource:** [credit_notes](../resources/credit-notes.md)
**Preview a credit note**
**Operation ID:** `GetCreditNotesPreview`

<p>Get a preview of a credit note without creating it.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `amount` | query | integer | No | The integer amount in cents (or local equivalent) representing the total amount of the credit note. One of `amount`, `lines`, or `shipping_cost` must be provided. |
| `credit_amount` | query | integer | No | The integer amount in cents (or local equivalent) representing the amount to credit the customer's balance, which will be automatically applied to their next invoice. |
| `effective_at` | query | integer (unix-time) | No | The date when this credit note is in effect. Same as `created` unless overwritten. When defined, this value replaces the system-generated 'Date of issue' printed on the credit note PDF. |
| `email_type` | query | enum: credit_note, none | No | Type of email to send to the customer, one of `credit_note` or `none` and the default is `credit_note`. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `invoice` | query | string | Yes | ID of the invoice. |
| `lines` | query | object[] | No | Line items that make up the credit note. One of `amount`, `lines`, or `shipping_cost` must be provided. |
| `memo` | query | string | No | The credit note's memo appears on the credit note PDF. |
| `metadata` | query | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. Individual keys can be unset by posting an empty value to them. All keys can be unset by posting an empty value to `metadata`. |
| `out_of_band_amount` | query | integer | No | The integer amount in cents (or local equivalent) representing the amount that is credited outside of Stripe. |
| `reason` | query | enum: duplicate, fraudulent, order_change... | No | Reason for issuing this credit note, one of `duplicate`, `fraudulent`, `order_change`, or `product_unsatisfactory` |
| `refund_amount` | query | integer | No | The integer amount in cents (or local equivalent) representing the amount to refund. If set, a refund will be created for the charge associated with the invoice. |
| `refunds` | query | object[] | No | Refunds to link to this credit note. |
| `shipping_cost` | query | object | No | When shipping_cost contains the shipping_rate from the invoice, the shipping_cost is included in the credit note. One of `amount`, `lines`, or `shipping_cost` must be provided. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[credit_note](../schemas/credit/credit-note.md)

