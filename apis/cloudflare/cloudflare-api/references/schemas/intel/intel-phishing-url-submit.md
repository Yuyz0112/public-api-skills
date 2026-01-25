# intel_phishing-url-submit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `excluded_urls` | object[] | No | URLs that were excluded from scanning because their domain is in our no-scan list. |
| `skipped_urls` | object[] | No | URLs that were skipped because the same URL is currently being scanned. |
| `submitted_urls` | object[] | No | URLs that were successfully submitted for scanning. |

## Nested Fields

### `excluded_urls`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No | URL that was excluded. |

### `skipped_urls`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No | URL that was skipped. |
| `url_id` | integer | No | ID of the submission of that URL that is currently scanning. |

### `submitted_urls`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No | URL that was submitted. |
| `url_id` | integer | No | ID assigned to this URL submission. Used to retrieve scanning results. |

