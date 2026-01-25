# DLP Datasets

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/dlp/datasets` | Fetch all datasets | [View](../operations/dlp-datasets-read-all.md) |
| POST | `/accounts/{account_id}/dlp/datasets` | Create a new dataset | [View](../operations/dlp-datasets-create.md) |
| GET | `/accounts/{account_id}/dlp/datasets/{dataset_id}` | Fetch a specific dataset | [View](../operations/dlp-datasets-read.md) |
| PUT | `/accounts/{account_id}/dlp/datasets/{dataset_id}` | Update details about a dataset | [View](../operations/dlp-datasets-update.md) |
| DELETE | `/accounts/{account_id}/dlp/datasets/{dataset_id}` | Delete a dataset | [View](../operations/dlp-datasets-delete.md) |
| POST | `/accounts/{account_id}/dlp/datasets/{dataset_id}/upload` | Prepare to upload a new version of a dataset | [View](../operations/dlp-datasets-create-version.md) |
| POST | `/accounts/{account_id}/dlp/datasets/{dataset_id}/upload/{version}` | Upload a new version of a dataset | [View](../operations/dlp-datasets-upload-version.md) |
| POST | `/accounts/{account_id}/dlp/datasets/{dataset_id}/versions/{version}` | Sets the column information for a multi-column upload | [View](../operations/dlp-datasets-define-columns.md) |
| POST | `/accounts/{account_id}/dlp/datasets/{dataset_id}/versions/{version}/entries/{entry_id}` | Upload a new version of a multi-column dataset | [View](../operations/dlp-datasets-upload-dataset-column.md) |
