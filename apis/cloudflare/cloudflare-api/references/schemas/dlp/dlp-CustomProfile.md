# dlp_CustomProfile

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ai_context_enabled` | boolean | No |  |
| `allowed_match_count` | integer (int32) | Yes | Related DLP policies will trigger when the match count exceeds the number set. |
| `confidence_threshold` | any | No |  |
| `context_awareness` | [dlp_ContextAwareness](dlp-ContextAwareness.md) | No |  |
| `created_at` | string (date-time) | Yes | When the profile was created. |
| `description` | string | No | The description of the profile. |
| `entries` | dlp_Entry[] | No |  |
| `id` | string (uuid) | Yes | The id of the profile (uuid). |
| `name` | string | Yes | The name of the profile. |
| `ocr_enabled` | boolean | Yes |  |
| `updated_at` | string (date-time) | Yes | When the profile was lasted updated. |

