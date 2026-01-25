# DELETE /accounts/{account_id}/cloudforce-one/events/tags/{tag_uuid}

**Resource:** [Tag](../resources/Tag.md)
**Deletes a tag (SoT)**
**Operation ID:** `delete_TagDelete`

Deletes a Source-of-Truth tag by UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `tag_uuid` | path | string | Yes | Tag UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the uuid of the deleted tag. |
| 400 | Bad Request. |
| 404 | Bad Request. |

## Security

- **api_token**
