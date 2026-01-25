# GET /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/indicators/{indicator_id}

**Resource:** [Indicator](../resources/Indicator.md)
**Reads an indicator**
**Operation ID:** `get_IndicatorRead`

Retrieves a specific indicator by its UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string | Yes | Dataset ID. |
| `indicator_id` | path | string | Yes | Indicator UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the indicator. |
| 404 | Bad Request. |

## Security

- **api_token**
