# PUT /accounts/{account_id}/access/tags/{tag_name}

**Resource:** [Access tags](../resources/Access-tags.md)
**Update a tag**
**Operation ID:** `access-tags-update-a-tag`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `tag_name` | path | access_tags_components-schemas-name | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [access_tag_without_app_count](../schemas/access/access-tag-without-app-count.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a tag response |
| 4XX | Update a tag response failure |

**Success Response Schema:**

[access_tags_components-schemas-single_response](../schemas/access/access-tags-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
