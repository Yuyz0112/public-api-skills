# dlp_NewPredefinedEntry

Used to create a new predefined or integration entry.

Predefined or integration entries can not be updated via the API so
these fields will update the entry's settings.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |
| `entry_id` | string (uuid) | Yes |  |
| `profile_id` | string (uuid) | No | This field is not used as the owning profile.
For predefined entries it is already set to a predefined profile. |

