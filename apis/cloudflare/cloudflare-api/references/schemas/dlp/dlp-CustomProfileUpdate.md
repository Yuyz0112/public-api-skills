# dlp_CustomProfileUpdate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ai_context_enabled` | boolean | No |  |
| `allowed_match_count` | integer (int32) | No |  |
| `confidence_threshold` | string | No |  |
| `context_awareness` | [dlp_ContextAwareness](dlp-ContextAwareness.md) | No |  |
| `description` | string | No | The description of the profile. |
| `entries` | dlp_ProfileEntryUpdate[] | No | Custom entries from this profile.
If this field is omitted, entries owned by this profile will not be changed. |
| `name` | string | Yes |  |
| `ocr_enabled` | boolean | No |  |
| `shared_entries` | dlp_SharedEntryUpdate[] | No | Other entries, e.g. predefined or integration. |

