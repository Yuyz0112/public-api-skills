# GET /accounts/{account_id}/cloudforce-one/events/indicatorTypes

**Resource:** [Indicator Types](../resources/Indicator-Types.md)
**Lists all indicator types**
**Operation ID:** `get_LegacyIndicatorTypesList`
⚠️ **Deprecated**

This Method is deprecated. Please use /events/dataset/:dataset_id/indicatorTypes instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of indicator types. |
| 400 | Bad Request. |

## Security

- **api_token**
