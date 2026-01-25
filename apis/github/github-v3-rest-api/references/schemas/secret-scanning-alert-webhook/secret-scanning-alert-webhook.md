# secret-scanning-alert-webhook

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `number` | [alert-number](alert-number.md) | No |  |
| `created_at` | [alert-created-at](alert-created-at.md) | No |  |
| `updated_at` | [nullable-alert-updated-at](nullable-alert-updated-at.md) | No |  |
| `url` | [alert-url](alert-url.md) | No |  |
| `html_url` | [alert-html-url](alert-html-url.md) | No |  |
| `locations_url` | string (uri) | No | The REST API URL of the code locations for this alert. |
| `resolution` | [secret-scanning-alert-resolution-webhook](secret-scanning-alert-resolution-webhook.md) | No |  |
| `resolved_at` | string (date-time) | No | The time that the alert was resolved in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `resolved_by` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `resolution_comment` | string | No | An optional comment to resolve an alert. |
| `secret_type` | string | No | The type of secret that secret scanning detected. |
| `secret_type_display_name` | string | No | User-friendly name for the detected secret, matching the `secret_type`.
For a list of built-in patterns, see "[Supported secret scanning patterns](https://docs.github.com/code-security/secret-scanning/introduction/supported-secret-scanning-patterns#supported-secrets)." |
| `validity` | enum: active, inactive, unknown | No | The token status as of the latest validity check. |
| `push_protection_bypassed` | boolean | No | Whether push protection was bypassed for the detected secret. |
| `push_protection_bypassed_by` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `push_protection_bypassed_at` | string (date-time) | No | The time that push protection was bypassed in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `push_protection_bypass_request_reviewer` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `push_protection_bypass_request_reviewer_comment` | string | No | An optional comment when reviewing a push protection bypass. |
| `push_protection_bypass_request_comment` | string | No | An optional comment when requesting a push protection bypass. |
| `push_protection_bypass_request_html_url` | string (uri) | No | The URL to a push protection bypass request. |
| `publicly_leaked` | boolean | No | Whether the detected secret was publicly leaked. |
| `multi_repo` | boolean | No | Whether the detected secret was found in multiple repositories in the same organization or business. |
| `assigned_to` | [nullable-simple-user](nullable-simple-user.md) | No |  |

