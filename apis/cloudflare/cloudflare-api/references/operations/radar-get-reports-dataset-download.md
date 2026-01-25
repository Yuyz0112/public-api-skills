# GET /radar/datasets/{alias}

**Resource:** [Radar Datasets](../resources/Radar-Datasets.md)
**Get dataset CSV stream**
**Operation ID:** `radar-get-reports-dataset-download`

Retrieves the CSV content of a given dataset by alias or ID. When getting the content by alias the latest dataset is returned, optionally filtered by the latest available at a given date.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `alias` | path | string | Yes | Dataset alias or ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**
