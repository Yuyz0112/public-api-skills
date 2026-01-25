# PATCH /accounts/{account_id}/cloudforce-one/events/tags/{tag_uuid}

**Resource:** [Tag](../resources/Tag.md)
**Updates a tag (SoT)**
**Operation ID:** `patch_TagUpdate`

Updates a Source-of-Truth tag by UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `tag_uuid` | path | string | Yes | Tag UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated tag. |
| 400 | Bad Request. |
| 404 | Bad Request. |

## Security

- **api_token**
