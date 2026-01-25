# dlp_PredefinedProfileConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ai_context_enabled` | boolean | No |  |
| `allowed_match_count` | integer (int32) | Yes |  |
| `confidence_threshold` | string | Yes |  |
| `enabled_entries` | string[] | Yes |  |
| `entries` | dlp_Entry[] | Yes |  |
| `id` | string (uuid) | Yes | The id of the predefined profile (uuid). |
| `name` | string | Yes | The name of the predefined profile. |
| `ocr_enabled` | boolean | No |  |
| `open_access` | boolean | No | Whether this profile can be accessed by anyone. |

