# organization-secret-scanning-alert

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
| `state` | [secret-scanning-alert-state](secret-scanning-alert-state.md) | No |  |
| `resolution` | [secret-scanning-alert-resolution](secret-scanning-alert-resolution.md) | No |  |
| `resolved_at` | string (date-time) | No | The time that the alert was resolved in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `resolved_by` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `secret_type` | string | No | The type of secret that secret scanning detected. |
| `secret_type_display_name` | string | No | User-friendly name for the detected secret, matching the `secret_type`.
For a list of built-in patterns, see "[Supported secret scanning patterns](https://docs.github.com/code-security/secret-scanning/introduction/supported-secret-scanning-patterns#supported-secrets)." |
| `secret` | string | No | The secret that was detected. |
| `repository` | [simple-repository](simple-repository.md) | No |  |
| `push_protection_bypassed` | boolean | No | Whether push protection was bypassed for the detected secret. |
| `push_protection_bypassed_by` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `push_protection_bypassed_at` | string (date-time) | No | The time that push protection was bypassed in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `push_protection_bypass_request_reviewer` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `push_protection_bypass_request_reviewer_comment` | string | No | An optional comment when reviewing a push protection bypass. |
| `push_protection_bypass_request_comment` | string | No | An optional comment when requesting a push protection bypass. |
| `push_protection_bypass_request_html_url` | string (uri) | No | The URL to a push protection bypass request. |
| `resolution_comment` | string | No | The comment that was optionally added when this alert was closed |
| `validity` | enum: active, inactive, unknown | No | The token status as of the latest validity check. |
| `publicly_leaked` | boolean | No | Whether the secret was publicly leaked. |
| `multi_repo` | boolean | No | Whether the detected secret was found in multiple repositories in the same organization or enterprise. |
| `is_base64_encoded` | boolean | No | A boolean value representing whether or not alert is base64 encoded |
| `first_location_detected` | [nullable-secret-scanning-first-detected-location](nullable-secret-scanning-first-detected-location.md) | No |  |
| `has_more_locations` | boolean | No | A boolean value representing whether or not the token in the alert was detected in more than one location. |
| `assigned_to` | [nullable-simple-user](nullable-simple-user.md) | No |  |

