# POST /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/indicatorTypes/create

**Resource:** [Indicators](../resources/Indicators.md)
**Create a new indicator type**
**Operation ID:** `post_IndicatorTypeCreate`

Creates a new indicator type and initializes its dedicated Durable Object

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string | Yes | Dataset ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicator type created successfully |
| 400 | Bad Request |
| 500 | Internal Server Error |

## Security

- **api_token**
