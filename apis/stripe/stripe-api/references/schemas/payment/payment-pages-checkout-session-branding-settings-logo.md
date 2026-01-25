# payment_pages_checkout_session_branding_settings_logo

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `file` | string | No | The ID of a [File upload](https://stripe.com/docs/api/files) representing the logo. Purpose must be `business_logo`. Required if `type` is `file` and disallowed otherwise. |
| `type` | enum: file, url | Yes | The type of image for the logo. Must be one of `file` or `url`. |
| `url` | string | No | The URL of the image. Present when `type` is `url`. |

