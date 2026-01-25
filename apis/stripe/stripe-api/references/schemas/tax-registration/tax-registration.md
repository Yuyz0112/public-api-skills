# tax.registration

A Tax `Registration` lets us know that your business is registered to collect tax on payments within a region, enabling you to [automatically collect tax](https://docs.stripe.com/tax).

Stripe doesn't register on your behalf with the relevant authorities when you create a Tax `Registration` object. For more information on how to register to collect tax, see [our guide](https://docs.stripe.com/tax/registering).

Related guide: [Using the Registrations API](https://docs.stripe.com/tax/registrations-api)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_from` | integer (unix-time) | Yes | Time at which the registration becomes active. Measured in seconds since the Unix epoch. |
| `country` | string | Yes | Two-letter country code ([ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)). |
| `country_options` | [tax_product_registrations_resource_country_options](tax-product-registrations-resource-country-options.md) | Yes |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `expires_at` | integer (unix-time) | No | If set, the registration stops being active at this time. If not set, the registration will be active indefinitely. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: tax.registration | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: active, expired, scheduled | Yes | The status of the registration. This field is present for convenience and can be deduced from `active_from` and `expires_at`. |

