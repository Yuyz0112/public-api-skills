# dlp_Dataset

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `case_sensitive` | boolean | No |  |
| `columns` | dlp_DatasetColumn[] | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `description` | string | No | The description of the dataset. |
| `encoding_version` | integer (int32) | Yes |  |
| `id` | string (uuid) | Yes |  |
| `name` | string | Yes |  |
| `num_cells` | integer (int64) | Yes |  |
| `secret` | boolean | Yes |  |
| `status` | [dlp_DatasetUploadStatus](dlp-DatasetUploadStatus.md) | Yes |  |
| `updated_at` | string (date-time) | Yes | Stores when the dataset was last updated.

This includes name or description changes as well as uploads. |
| `uploads` | dlp_DatasetUpload[] | Yes |  |

