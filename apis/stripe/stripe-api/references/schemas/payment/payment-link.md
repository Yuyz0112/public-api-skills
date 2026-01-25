# payment_link

A payment link is a shareable URL that will take your customers to a hosted payment page. A payment link can be shared and used multiple times.

When a customer opens a payment link it will open a new [checkout session](https://docs.stripe.com/api/checkout/sessions) to render the payment page. You can use [checkout session events](https://docs.stripe.com/api/events/types#event_types-checkout.session.completed) to track payments through payment links.

Related guide: [Payment Links API](https://docs.stripe.com/payment-links)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Whether the payment link's `url` is active. If `false`, customers visiting the URL will be shown a page saying that the link has been deactivated. |
| `after_completion` | [payment_links_resource_after_completion](payment-links-resource-after-completion.md) | Yes |  |
| `allow_promotion_codes` | boolean | Yes | Whether user redeemable promotion codes are enabled. |
| `application` | any | No | The ID of the Connect application that created the Payment Link. |
| `application_fee_amount` | integer | No | The amount of the application fee (if any) that will be requested to be applied to the payment and transferred to the application owner's Stripe account. |
| `application_fee_percent` | number | No | This represents the percentage of the subscription invoice total that will be transferred to the application owner's Stripe account. |
| `automatic_tax` | [payment_links_resource_automatic_tax](payment-links-resource-automatic-tax.md) | Yes |  |
| `billing_address_collection` | enum: auto, required | Yes | Configuration for collecting the customer's billing address. Defaults to `auto`. |
| `consent_collection` | any | No | When set, provides configuration to gather active consent from customers. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `custom_fields` | payment_links_resource_custom_fields[] | Yes | Collect additional information from your customer using custom fields. Up to 3 fields are supported. You can't set this parameter if `ui_mode` is `custom`. |
| `custom_text` | [payment_links_resource_custom_text](payment-links-resource-custom-text.md) | Yes |  |
| `customer_creation` | enum: always, if_required | Yes | Configuration for Customer creation during checkout. |
| `id` | string | Yes | Unique identifier for the object. |
| `inactive_message` | string | No | The custom message to be displayed to a customer when a payment link is no longer active. |
| `invoice_creation` | any | No | Configuration for creating invoice for payment mode payment links. |
| `line_items` | object | No | The line items representing what is being sold. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name_collection` | [payment_links_resource_name_collection](payment-links-resource-name-collection.md) | No |  |
| `object` | enum: payment_link | Yes | String representing the object's type. Objects of the same type share the same value. |
| `on_behalf_of` | any | No | The account on behalf of which to charge. See the [Connect documentation](https://support.stripe.com/questions/sending-invoices-on-behalf-of-connected-accounts) for details. |
| `optional_items` | payment_links_resource_optional_item[] | No | The optional items presented to the customer at checkout. |
| `payment_intent_data` | any | No | Indicates the parameters to be passed to PaymentIntent creation during checkout. |
| `payment_method_collection` | enum: always, if_required | Yes | Configuration for collecting a payment method during checkout. Defaults to `always`. |
| `payment_method_types` | string[] | No | The list of payment method types that customers can use. When `null`, Stripe will dynamically show relevant payment methods you've enabled in your [payment method settings](https://dashboard.stripe.com/settings/payment_methods). |
| `phone_number_collection` | [payment_links_resource_phone_number_collection](payment-links-resource-phone-number-collection.md) | Yes |  |
| `restrictions` | any | No | Settings that restrict the usage of a payment link. |
| `shipping_address_collection` | any | No | Configuration for collecting the customer's shipping address. |
| `shipping_options` | payment_links_resource_shipping_option[] | Yes | The shipping rate options applied to the session. |
| `submit_type` | enum: auto, book, donate... | Yes | Indicates the type of transaction being performed which customizes relevant text on the page, such as the submit button. |
| `subscription_data` | any | No | When creating a subscription, the specified configuration data will be used. There must be at least one line item with a recurring price to use `subscription_data`. |
| `tax_id_collection` | [payment_links_resource_tax_id_collection](payment-links-resource-tax-id-collection.md) | Yes |  |
| `transfer_data` | any | No | The account (if any) the payments will be attributed to for tax reporting, and where funds from each payment will be transferred to. |
| `url` | string | Yes | The public URL that can be shared with customers. |

## Nested Fields

### `line_items`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

