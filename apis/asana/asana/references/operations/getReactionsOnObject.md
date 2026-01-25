# GET /reactions

**Resource:** [Reactions](../resources/Reactions.md)
**Get reactions with an emoji base on an object.**
**Operation ID:** `getReactionsOnObject`

Returns the reactions with a specified emoji base character on the object.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `target` | query | string | Yes | Globally unique identifier for object to fetch reactions from. Must be a GID for a status update or story. |
| `emoji_base` | query | string | Yes | Only return reactions with this emoji base character. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified object's reactions. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
