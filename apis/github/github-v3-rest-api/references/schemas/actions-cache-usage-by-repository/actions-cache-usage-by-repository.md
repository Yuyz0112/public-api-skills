# actions-cache-usage-by-repository

GitHub Actions Cache Usage by repository.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `full_name` | string | Yes | The repository owner and name for the cache usage being shown. |
| `active_caches_size_in_bytes` | integer | Yes | The sum of the size in bytes of all the active cache items in the repository. |
| `active_caches_count` | integer | Yes | The number of active caches in the repository. |

