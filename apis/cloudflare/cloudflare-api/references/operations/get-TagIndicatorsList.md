# GET /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/tags/{tag_uuid}/indicators

**Resource:** [Tag](../resources/Tag.md)
**List indicators related to a tag**
**Operation ID:** `get_TagIndicatorsList`

Returns indicators associated with the provided tag UUID across all indicator datasets, with pagination.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `tag_uuid` | path | string | Yes | Tag UUID. |
| `dataset_id` | path | string (uuid) | Yes | Dataset UUID. |
| `page` | query | number | No |  |
| `pageSize` | query | number | No |  |
| `indicatorType` | query | string | No |  |
| `relatedEvent` | query | string[] | No | Filter indicators by related event UUID(s). Multiple UUIDs can be provided by repeating the parameter. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a paginated list of indicators. |
| 400 | Bad Request. |
| 404 | Bad Request. |
| 500 | Bad Request. |

## Security

- **api_token**
