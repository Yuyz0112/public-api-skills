# GET /radar/datasets

**Resource:** [Radar Datasets](../resources/Radar-Datasets.md)
**List datasets**
**Operation ID:** `radar-get-reports-datasets`

Retrieves a list of datasets.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `offset` | query | integer | No | Skips the specified number of objects before fetching the results. |
| `datasetType` | query | enum: RANKING_BUCKET, REPORT | No | Filters results by dataset type. |
| `date` | query | string (date) | No | Filters results by the specified date. |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**
