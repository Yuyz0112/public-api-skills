# POST /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/indicators/create

**Resource:** [Indicator](../resources/Indicator.md)
**Creates a new indicator**
**Operation ID:** `post_IndicatorCreate`

Creates a new indicator with the specified type and related datasets.

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
| 200 | Returns the created indicator. |
| 400 | Bad Request. |

## Security

- **api_token**
