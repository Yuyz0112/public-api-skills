# zero-trust-gateway_notification_settings

Configure the message the user's device shows during an antivirus scan.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Specify whether to enable notifications. |
| `include_context` | boolean | No | Specify whether to include context information as query parameters. |
| `msg` | string | No | Specify the message to show in the notification. |
| `support_url` | string | No | Specify a URL that directs users to more information. If unset, the notification opens a block page. |

