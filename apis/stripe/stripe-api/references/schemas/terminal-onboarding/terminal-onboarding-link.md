# terminal.onboarding_link

Returns redirect links used for onboarding onto Tap to Pay on iPhone.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `link_options` | [terminal_onboarding_link_link_options](terminal-onboarding-link-link-options.md) | Yes |  |
| `link_type` | enum: apple_terms_and_conditions | Yes | The type of link being generated. |
| `object` | enum: terminal.onboarding_link | Yes |  |
| `on_behalf_of` | string | No | Stripe account ID to generate the link for. |
| `redirect_url` | string | Yes | The link passed back to the user for their onboarding. |

