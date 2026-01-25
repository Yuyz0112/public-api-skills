# dlp_NewCustomProfile

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ai_context_enabled` | boolean | No |  |
| `allowed_match_count` | integer (int32) | No | Related DLP policies will trigger when the match count exceeds the number set. |
| `confidence_threshold` | string | No |  |
| `context_awareness` | [dlp_ContextAwareness](dlp-ContextAwareness.md) | No |  |
| `description` | string | No | The description of the profile. |
| `entries` | dlp_EntryOfNewProfile[] | No |  |
| `name` | string | Yes |  |
| `ocr_enabled` | boolean | No |  |
| `shared_entries` | dlp_NewSharedEntry[] | No | Entries from other profiles (e.g. pre-defined Cloudflare profiles, or your Microsoft Information Protection profiles). |

