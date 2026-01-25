# ExtensionSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `icon_url` | string (url) | No | A small logo, 18-by-18 pixels. |
| `logo_url` | string (url) | No | A large logo, 75 pixels high and no more than 300 pixels wide. |
| `label` | string | No | Human friendly display label |
| `key` | string | No | Machine friendly display label |
| `description` | string | No | The long description for the Extension |
| `guide_url` | string (url) | No | A link to the extension's support guide |
| `send_types` | string[] | No | The types of PagerDuty incident events that will activate this Extension |
| `url` | string | No | The url that the webhook payload will be sent to for this Extension. |

