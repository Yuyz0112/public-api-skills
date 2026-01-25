# StatusPage

A Status Page with all the configuration needed to present the system status in a public or private manner.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | An unique identifier within Status Page scope that defines a Status Page entry. |
| `name` | string | No | The name of a Status Page to be presented as a brand title (for example, the rendered Status Page HTML header). |
| `published_at` | string (date-time) | No | The date time moment when a Status Page was published to be publicly available. |
| `status_page_type` | enum: public, private | No | The type of Status Pages to retrieve - public is accessible to everyone on the internet or private requiring some sort of authentication/authorization layer. |
| `url` | string (url) | No | The URL from which the Status Page can be accessed on the internet (either customer's domain or default *.trust.pagerduty.com). |
| `type` | string | No | A string that determines the schema of the object. This must be the standard name for the entity, suffixed by _reference if the object is a reference. |

