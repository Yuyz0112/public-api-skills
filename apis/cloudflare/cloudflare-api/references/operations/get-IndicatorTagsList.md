# GET /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/indicators/tags

**Resource:** [Indicator](../resources/Indicator.md)
**List mirrored tags for an indicator dataset**
**Operation ID:** `get_IndicatorTagsList`

Returns all mirrored tags from the indicator dataset (DO mirror table). No pagination.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string | Yes | Dataset ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns an array of mirrored tags. |
| 400 | Bad Request. |
| 404 | Bad Request. |
| 500 | Bad Request. |

## Security

- **api_token**
