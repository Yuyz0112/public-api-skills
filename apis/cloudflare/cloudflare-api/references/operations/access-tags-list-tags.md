# GET /accounts/{account_id}/access/tags

**Resource:** [Access tags](../resources/Access-tags.md)
**List tags**
**Operation ID:** `access-tags-list-tags`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List tags response |
| 4XX | List tags response failure |

**Success Response Schema:**

[access_tags_components-schemas-response_collection](../schemas/access/access-tags-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
