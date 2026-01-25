# PATCH /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/indicators/{indicator_id}

**Resource:** [Indicator](../resources/Indicator.md)
**Updates an indicator**
**Operation ID:** `patch_IndicatorUpdate`

Updates an existing indicator's properties.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string | Yes | Dataset ID. |
| `indicator_id` | path | string | Yes | Indicator UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated indicator. |
| 400 | Bad Request. |
| 404 | Bad Request. |

## Security

- **api_token**
