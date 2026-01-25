# POST /accounts/{account_id}/access/tags

**Resource:** [Access tags](../resources/Access-tags.md)
**Create a tag**
**Operation ID:** `access-tags-create-tag`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create a tag response |
| 4XX | Create a tag response failure |

**Success Response Schema:**

[access_tags_components-schemas-single_response](../schemas/access/access-tags-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
