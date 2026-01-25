# GET /accounts/{account_id}/cloudforce-one/events/indicator-types

**Resource:** [Indicator Types](../resources/Indicator-Types.md)
**Lists indicator types across multiple datasets**
**Operation ID:** `get_IndicatorTypesList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `datasetIds` | query | string[] | No | Array of dataset IDs to query indicator types from. If not provided, queries all datasets for the account. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of indicator types. |
| 400 | Bad Request. |

## Security

- **api_token**
