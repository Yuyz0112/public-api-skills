# payment_links_resource_consent_collection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `payment_method_reuse_agreement` | any | No | Settings related to the payment method reuse text shown in the Checkout UI. |
| `promotions` | enum: auto, none | No | If set to `auto`, enables the collection of customer consent for promotional communications. |
| `terms_of_service` | enum: none, required | No | If set to `required`, it requires cutomers to accept the terms of service before being able to pay. If set to `none`, customers won't be shown a checkbox to accept the terms of service. |

