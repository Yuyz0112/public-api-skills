# POST /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/indicators/bulk

**Resource:** [Indicator](../resources/Indicator.md)
**Creates multiple indicators in bulk**
**Operation ID:** `post_IndicatorCreateBulk`

Creates multiple indicators at once with their respective types and related datasets.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string (uuid) | Yes | Dataset UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the number of created indicators. |
| 400 | Bad Request. |

## Security

- **api_token**
