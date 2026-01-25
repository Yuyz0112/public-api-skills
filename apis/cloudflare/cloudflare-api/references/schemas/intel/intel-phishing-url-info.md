# intel_phishing-url-info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `categorizations` | object[] | No | List of categorizations applied to this submission. |
| `model_results` | object[] | No | List of model results for completed scans. |
| `rule_matches` | object[] | No | List of signatures that matched against site content found when crawling the URL. |
| `scan_status` | object | No | Status of the most recent scan found. |
| `screenshot_download_signature` | string | No | For internal use. |
| `screenshot_path` | string | No | For internal use. |
| `url` | string | No | URL that was submitted. |

## Nested Fields

### `categorizations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `category` | string | No | Name of the category applied. |
| `verification_status` | string | No | Result of human review for this categorization. |

### `model_results`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model_name` | string | No | Name of the model. |
| `model_score` | number | No | This is the score that is outputted by the model for this submission. |

### `rule_matches`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `banning` | boolean | No | For internal use. |
| `blocking` | boolean | No | For internal use. |
| `description` | string | No | Description of the signature that matched. |
| `name` | string | No | Name of the signature that matched. |

### `scan_status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `last_processed` | string | No | Timestamp of when the submission was processed. |
| `scan_complete` | boolean | No | For internal use. |
| `status_code` | integer | No | Status code that the crawler received when loading the submitted URL. |
| `submission_id` | integer | No | ID of the most recent submission. |

