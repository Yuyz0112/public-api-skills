# POST /accounts/{account_id}/cloudforce-one/events/tags/create

**Resource:** [Tag](../resources/Tag.md)
**Creates a new tag**
**Operation ID:** `post_TagCreate`

Creates a new tag to be used accross threat events.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created tag. |
| 400 | Bad Request. |
| 404 | Bad Request. |

## Security

- **api_token**
