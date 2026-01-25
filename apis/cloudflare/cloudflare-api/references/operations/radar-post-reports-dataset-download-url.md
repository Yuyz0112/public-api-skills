# POST /radar/datasets/download

**Resource:** [Radar Datasets](../resources/Radar-Datasets.md)
**Get dataset download URL**
**Operation ID:** `radar-post-reports-dataset-download-url`

Retrieves an URL to download a single dataset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**
