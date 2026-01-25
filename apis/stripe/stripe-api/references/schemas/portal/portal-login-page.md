# portal_login_page

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes | If `true`, a shareable `url` will be generated that will take your customers to a hosted login page for the customer portal.

If `false`, the previously generated `url`, if any, will be deactivated. |
| `url` | string | No | A shareable URL to the hosted portal login page. Your customers will be able to log in with their [email](https://docs.stripe.com/api/customers/object#customer_object-email) and receive a link to their customer portal. |

