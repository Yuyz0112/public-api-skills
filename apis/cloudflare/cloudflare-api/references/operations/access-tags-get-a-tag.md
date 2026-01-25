# GET /accounts/{account_id}/access/tags/{tag_name}

**Resource:** [Access tags](../resources/Access-tags.md)
**Get a tag**
**Operation ID:** `access-tags-get-a-tag`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `tag_name` | path | access_tags_components-schemas-name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a tag response |
| 4XX | Get a tag response failure |

**Success Response Schema:**

[access_tags_components-schemas-single_response](../schemas/access/access-tags-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
