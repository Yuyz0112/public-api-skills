# GET /accounts/{account_id}/cloudforce-one/events/categories

**Resource:** [Category](../resources/Category.md)
**Lists categories across multiple datasets**
**Operation ID:** `get_CategoryList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `datasetIds` | query | string[] | No | Array of dataset IDs to query categories from. If not provided, uses the default dataset. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of categories. |
| 400 | Bad Request. |

## Security

- **api_token**
