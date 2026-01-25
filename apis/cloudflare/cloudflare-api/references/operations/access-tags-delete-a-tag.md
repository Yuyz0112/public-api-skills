# DELETE /accounts/{account_id}/access/tags/{tag_name}

**Resource:** [Access tags](../resources/Access-tags.md)
**Delete a tag**
**Operation ID:** `access-tags-delete-a-tag`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `tag_name` | path | access_tags_components-schemas-name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete a tag response |
| 4XX | Delete a tag response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
