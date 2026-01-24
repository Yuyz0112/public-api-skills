# GET /v1/credit_notes/preview/lines

**Resource:** [credit_notes](../resources/credit-notes.md)
**Retrieve a credit note preview's line items**
**Operation ID:** `GetCreditNotesPreviewLines`

<p>When retrieving a credit note preview, you’ll get a <strong>lines</strong> property containing the first handful of those items. This URL you can retrieve the full (paginated) list of line items.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `amount` | query | integer | No | The integer amount in cents (or local equivalent) representing the total amount of the credit note. One of `amount`, `lines`, or `shipping_cost` must be provided. |
| `credit_amount` | query | integer | No | The integer amount in cents (or local equivalent) representing the amount to credit the customer's balance, which will be automatically applied to their next invoice. |
| `effective_at` | query | integer (unix-time) | No | The date when this credit note is in effect. Same as `created` unless overwritten. When defined, this value replaces the system-generated 'Date of issue' printed on the credit note PDF. |
| `email_type` | query | enum: credit_note, none | No | Type of email to send to the customer, one of `credit_note` or `none` and the default is `credit_note`. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `invoice` | query | string | Yes | ID of the invoice. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `lines` | query | object[] | No | Line items that make up the credit note. One of `amount`, `lines`, or `shipping_cost` must be provided. |
| `memo` | query | string | No | The credit note's memo appears on the credit note PDF. |
| `metadata` | query | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. Individual keys can be unset by posting an empty value to them. All keys can be unset by posting an empty value to `metadata`. |
| `out_of_band_amount` | query | integer | No | The integer amount in cents (or local equivalent) representing the amount that is credited outside of Stripe. |
| `reason` | query | enum: duplicate, fraudulent, order_change... | No | Reason for issuing this credit note, one of `duplicate`, `fraudulent`, `order_change`, or `product_unsatisfactory` |
| `refund_amount` | query | integer | No | The integer amount in cents (or local equivalent) representing the amount to refund. If set, a refund will be created for the charge associated with the invoice. |
| `refunds` | query | object[] | No | Refunds to link to this credit note. |
| `shipping_cost` | query | object | No | When shipping_cost contains the shipping_rate from the invoice, the shipping_cost is included in the credit note. One of `amount`, `lines`, or `shipping_cost` must be provided. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

