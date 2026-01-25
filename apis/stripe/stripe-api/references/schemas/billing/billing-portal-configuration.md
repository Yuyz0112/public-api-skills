# billing_portal.configuration

A portal configuration describes the functionality and behavior you embed in a portal session. Related guide: [Configure the customer portal](/customer-management/configure-portal).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Whether the configuration is active and can be used to create portal sessions. |
| `application` | any | No | ID of the Connect Application that created the configuration. |
| `business_profile` | [portal_business_profile](portal-business-profile.md) | Yes |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `default_return_url` | string | No | The default URL to redirect customers to when they click on the portal's link to return to your website. This can be [overriden](https://docs.stripe.com/api/customer_portal/sessions/create#create_portal_session-return_url) when creating the session. |
| `features` | [portal_features](portal-features.md) | Yes |  |
| `id` | string | Yes | Unique identifier for the object. |
| `is_default` | boolean | Yes | Whether the configuration is the default. If `true`, this configuration can be managed in the Dashboard and portal sessions will use this configuration unless it is overriden when creating the session. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `login_page` | [portal_login_page](portal-login-page.md) | Yes |  |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | No | The name of the configuration. |
| `object` | enum: billing_portal.configuration | Yes | String representing the object's type. Objects of the same type share the same value. |
| `updated` | integer (unix-time) | Yes | Time at which the object was last updated. Measured in seconds since the Unix epoch. |

