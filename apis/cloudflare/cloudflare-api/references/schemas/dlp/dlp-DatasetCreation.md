# dlp_DatasetCreation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dataset` | [dlp_Dataset](dlp-Dataset.md) | Yes |  |
| `encoding_version` | integer (int32) | Yes | Encoding version to use for dataset. |
| `max_cells` | integer (int64) | Yes |  |
| `secret` | string (password) | No | The secret to use for Exact Data Match datasets.

This is not present in Custom Wordlists. |
| `version` | integer (int64) | Yes | The version to use when uploading the dataset. |

