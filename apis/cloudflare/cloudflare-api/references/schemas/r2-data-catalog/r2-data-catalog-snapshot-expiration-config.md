# r2-data-catalog_snapshot-expiration-config

Configures snapshot expiration settings.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `max_snapshot_age` | string | Yes | Specifies the maximum age for snapshots. The system deletes snapshots older than this age.
Format: <number><unit> where unit is d (days), h (hours), m (minutes), or s (seconds).
Examples: "7d" (7 days), "48h" (48 hours), "2880m" (2,880 minutes).
 |
| `min_snapshots_to_keep` | integer (int64) | Yes | Specifies the minimum number of snapshots to retain. |
| `state` | [r2-data-catalog_catalog-maintenance-state](r2-data-catalog-catalog-maintenance-state.md) | Yes |  |

