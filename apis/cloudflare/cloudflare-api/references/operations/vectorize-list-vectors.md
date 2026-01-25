# GET /accounts/{account_id}/vectorize/v2/indexes/{index_name}/list

**Resource:** [Vectorize](../resources/Vectorize.md)
**List Vectors**
**Operation ID:** `vectorize-list-vectors`

Returns a paginated list of vector identifiers from the specified index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |
| `index_name` | path | vectorize_index-name | Yes |  |
| `count` | query | integer | No |  |
| `cursor` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Vectors Response |
| 4XX | List Vectors Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
