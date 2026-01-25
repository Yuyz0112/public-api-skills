# product

Products describe the specific goods or services you offer to your customers.
For example, you might offer a Standard and Premium version of your goods or service; each version would be a separate Product.
They can be used in conjunction with [Prices](https://api.stripe.com#prices) to configure pricing in Payment Links, Checkout, and Subscriptions.

Related guides: [Set up a subscription](https://docs.stripe.com/billing/subscriptions/set-up-subscription),
[share a Payment Link](https://docs.stripe.com/payment-links),
[accept payments with Checkout](https://docs.stripe.com/payments/accept-a-payment#create-product-prices-upfront),
and more about [Products and Prices](https://docs.stripe.com/products-prices/overview)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Whether the product is currently available for purchase. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `default_price` | any | No | The ID of the [Price](https://docs.stripe.com/api/prices) object that is the default price for this product. |
| `description` | string | No | The product's description, meant to be displayable to the customer. Use this field to optionally store a long form explanation of the product being sold for your own rendering purposes. |
| `id` | string | Yes | Unique identifier for the object. |
| `images` | string[] | Yes | A list of up to 8 URLs of images for this product, meant to be displayable to the customer. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `marketing_features` | product_marketing_feature[] | Yes | A list of up to 15 marketing features for this product. These are displayed in [pricing tables](https://docs.stripe.com/payments/checkout/pricing-table). |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | Yes | The product's name, meant to be displayable to the customer. |
| `object` | enum: product | Yes | String representing the object's type. Objects of the same type share the same value. |
| `package_dimensions` | any | No | The dimensions of this product for shipping purposes. |
| `shippable` | boolean | No | Whether this product is shipped (i.e., physical goods). |
| `statement_descriptor` | string | No | Extra information about a product which will appear on your customer's credit card statement. In the case that multiple products are billed at once, the first statement descriptor will be used. Only used for subscription payments. |
| `tax_code` | any | No | A [tax code](https://docs.stripe.com/tax/tax-categories) ID. |
| `unit_label` | string | No | A label that represents units of this product. When set, this will be included in customers' receipts, invoices, Checkout, and the customer portal. |
| `updated` | integer (unix-time) | Yes | Time at which the object was last updated. Measured in seconds since the Unix epoch. |
| `url` | string | No | A URL of a publicly-accessible webpage for this product. |

