# zero-trust-gateway_block-page-settings

Specify block page layout settings.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `background_color` | string | No | Specify the block page background color in `#rrggbb` format when the mode is customized_block_page. |
| `enabled` | boolean | No | Specify whether to enable the custom block page. |
| `footer_text` | string | No | Specify the block page footer text when the mode is customized_block_page. |
| `header_text` | string | No | Specify the block page header text when the mode is customized_block_page. |
| `include_context` | boolean | No | Specify whether to append context to target_uri as query parameters. This applies only when the mode is redirect_uri. |
| `logo_path` | string | No | Specify the full URL to the logo file when the mode is customized_block_page. |
| `mailto_address` | string | No | Specify the admin email for users to contact when the mode is customized_block_page. |
| `mailto_subject` | string | No | Specify the subject line for emails created from the block page when the mode is customized_block_page. |
| `mode` | enum: , customized_block_page, redirect_uri | No | Specify whether to redirect users to a Cloudflare-hosted block page or a customer-provided URI. |
| `name` | string | No | Specify the block page title when the mode is customized_block_page. |
| `read_only` | boolean | No | Indicate that this setting was shared via the Orgs API and read only for the current account. |
| `source_account` | string | No | Indicate the account tag of the account that shared this setting. |
| `suppress_footer` | boolean | No | Specify whether to suppress detailed information at the bottom of the block page when the mode is customized_block_page. |
| `target_uri` | string (uri) | No | Specify the URI to redirect users to when the mode is redirect_uri. |
| `version` | integer | No | Indicate the version number of the setting. |

