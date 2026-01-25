# GET /accounts/{account_id}/cloudforce-one/events/tags

**Resource:** [Tag](../resources/Tag.md)
**Lists all tags (SoT)**
**Operation ID:** `get_TagList`

Returns all Source-of-Truth tags for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `page` | query | number | No |  |
| `pageSize` | query | number | No |  |
| `search` | query | string | No |  |
| `categoryUuid` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a paginated list of tags. |
| 400 | Bad Request. |

## Security

- **api_token**
