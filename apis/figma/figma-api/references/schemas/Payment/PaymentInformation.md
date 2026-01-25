# PaymentInformation

An object describing a user's payment information for a plugin, widget, or Community file.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `user_id` | string | Yes | The ID of the user whose payment information was queried. Can be used to verify the validity of a response. |
| `resource_id` | string | Yes | The ID of the plugin, widget, or Community file that was queried. Can be used to verify the validity of a response. |
| `resource_type` | enum: PLUGIN, WIDGET, COMMUNITY_FILE | Yes | The type of the resource. |
| `payment_status` | [PaymentStatus](PaymentStatus.md) | Yes |  |
| `date_of_purchase` | string (date-time) | No | The UTC ISO 8601 timestamp indicating when the user purchased the resource. No value is given if the user has never purchased the resource.
  
Note that a value will still be returned if the user had purchased the resource, but no longer has active access to it (e.g. purchase refunded, subscription ended). |

